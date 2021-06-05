---
ns: MISC
---
## GET_DISTANCE_BETWEEN_COORDS

```c
// 0x0BE7F4E3CDBAFB28 0xF698765E
float GET_DISTANCE_BETWEEN_COORDS(float x1, float y1, float z1, float x2, float y2, float z2, BOOL useZ);
```

If useZ is false, only the 2D plane (X-Y) will be considered for calculating the distance.
Consider using this faster native instead: SYSTEM::VDIST - DVIST always takes in consideration the 3D coordinates.

```
NativeDB Introduced: v1207
```

## Parameters
* **x1**:
* **y1**:
* **z1**:
* **x2**:
* **y2**:
* **z2**:
* **useZ**:
