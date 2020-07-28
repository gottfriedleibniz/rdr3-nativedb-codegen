---
ns: VEHICLE
---
## IS_VEHICLE_SEAT_FREE

```c
// 0xE052C1B1CAA4ECE4 0xDAF42B02
BOOL IS_VEHICLE_SEAT_FREE(Vehicle vehicle, int seatIndex);
```

```
Check if a vehicle seat is free.
-1 being the driver seat.
Use GET_VEHICLE_MAX_NUMBER_OF_PASSENGERS(vehicle) - 1 for last seat index.
```

## Parameters
* **vehicle**:
* **seatIndex**:
