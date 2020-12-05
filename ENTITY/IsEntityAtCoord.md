---
ns: ENTITY
---
## IS_ENTITY_AT_COORD

```c
// 0x5E58342602E94718 0xD749B606
BOOL IS_ENTITY_AT_COORD(Entity entity, float xPos, float yPos, float zPos, float xSize, float ySize, float zSize, BOOL p7, BOOL p8, int p9);
```

```
Checks if entity is within x/y/zSize distance of x/y/z. 

Last three are unknown ints, almost always p7 = 0, p8 = 1, p9 = 0

NativeDB Introduced: v1207
```

## Parameters
* **entity**:
* **xPos**:
* **yPos**:
* **zPos**:
* **xSize**:
* **ySize**:
* **zSize**:
* **p7**:
* **p8**:
* **p9**:
