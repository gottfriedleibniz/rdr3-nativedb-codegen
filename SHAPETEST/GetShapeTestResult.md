---
ns: SHAPETEST
---
## GET_SHAPE_TEST_RESULT

```c
// 0xEDE8AC7C5108FB1D 0xF3C2875A
int GET_SHAPE_TEST_RESULT(int shapeTestHandle, BOOL* hit, Vector3* endCoords, Vector3* surfaceNormal, Entity* entityHit);
```

Returns the result of a shape test: 0 if the handle is invalid, 1 if the shape test is still pending, or 2 if the shape test has completed, and the handle should be invalidated.
When used with an asynchronous shape test, this native should be looped until returning 0 or 2, after which the handle is invalidated.

```
NativeDB Introduced: v1207
```

## Parameters
* **shapeTestHandle**:
* **hit**:
* **endCoords**:
* **surfaceNormal**:
* **entityHit**:
