---
ns: VEHICLE
---
## GET_VEHICLE_NUMBER_OF_PASSENGERS

```c
// 0x59F3F16577CD79B2 0x1EF20849
int GET_VEHICLE_NUMBER_OF_PASSENGERS(Vehicle vehicle);
```

```
Gets the number of passengers, NOT including the driver. Use IS_VEHICLE_SEAT_FREE(Vehicle, -1) to also check for the driver

NativeDB Introduced: v1207
```

## Parameters
* **vehicle**:
