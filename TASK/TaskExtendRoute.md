---
ns: TASK
---
## TASK_EXTEND_ROUTE

```c
// 0x1E7889778264843A 0x43271F69
void TASK_EXTEND_ROUTE(float x, float y, float z);
```

Adds a new point to the current point route. Call TASK_FLUSH_ROUTE before the first call to this. Call TASK_FOLLOW_POINT_ROUTE to make the Ped go the route.
A maximum of 8 points can be added.

```
NativeDB Introduced: v1207
```

## Parameters
* **x**:
* **y**:
* **z**:
