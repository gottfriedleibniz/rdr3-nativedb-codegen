---
ns: VEHICLE
---
## GET_ROTATION_OF_VEHICLE_RECORDING_AT_TIME

```c
// 0x61787DD28B8CC0D5 0xD96DEC68
Vector3 GET_ROTATION_OF_VEHICLE_RECORDING_AT_TIME(int recording, float time, char* script);
```

This native does no interpolation between pathpoints. The same rotation will be returned for all times up to the next pathpoint in the recording.
See REQUEST_VEHICLE_RECORDING

```
NativeDB Introduced: v1207
```

## Parameters
* **recording**:
* **time**:
* **script**:
