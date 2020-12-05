---
ns: VEHICLE
---
## DELETE_VEHICLE

```c
// 0xE20A909D8C4A70F8 0x9803AF60
void DELETE_VEHICLE(Vehicle* vehicle);
```

```
Deletes a vehicle.
The vehicle must be a mission entity to delete, so call this before deleting: SET_ENTITY_AS_MISSION_ENTITY(vehicle, true, true);

eg how to use:
SET_ENTITY_AS_MISSION_ENTITY(vehicle, true, true);
DELETE_VEHICLE(&vehicle);

Deletes the specified vehicle, then sets the handle pointed to by the pointer to NULL.

NativeDB Introduced: v1207
```

## Parameters
* **vehicle**:
