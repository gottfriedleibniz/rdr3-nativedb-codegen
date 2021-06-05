---
ns: ENTITY
---
## APPLY_FORCE_TO_ENTITY_CENTER_OF_MASS

```c
// 0x31DA7CEC5334DB37 0x28924E98
void APPLY_FORCE_TO_ENTITY_CENTER_OF_MASS(Entity entity, int forceType, float x, float y, float z, BOOL p5, BOOL isDirectionRel, BOOL isForceRel, BOOL p8);
```

p6/relative - makes the xyz force not relative to world coords, but to something else
p7/highForce - setting false will make the force really low

```
NativeDB Introduced: v1207
```

## Parameters
* **entity**:
* **forceType**:
* **x**:
* **y**:
* **z**:
* **p5**:
* **isDirectionRel**:
* **isForceRel**:
* **p8**:
