---
ns: VEHICLE
---
## START_VEHICLE_HORN

```c
// 0xB4E3BFC39CA16057 0x0DF5ADB3
void START_VEHICLE_HORN(Vehicle vehicle, int duration, Hash mode, BOOL forever);
```

Sounds the horn for the specified vehicle.
vehicle: The vehicle to activate the horn for.
mode: The hash of "NORMAL" or "HELDDOWN". Can be 0.
duration: The duration to sound the horn, in milliseconds.
Note: If a player is in the vehicle, it will only sound briefly.

```
NativeDB Introduced: v1207
```

## Parameters
* **vehicle**:
* **duration**:
* **mode**:
* **forever**:
