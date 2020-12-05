---
ns: TASK
---
## TASK_DISMOUNT_ANIMAL

```c
// 0x48E92D3DDE23C23A
void TASK_DISMOUNT_ANIMAL(Ped rider, int taskFlag, Any p2, Any p3, Any p4, Any p5);
```

```
Dismounts the ped from the animal it's mounted on. taskFlag affects what side the rider gets off. 1 << 18 will get off on the left side, where any other value will get off on the right side. The only other known value are 1 << 17 and 1 << 24, which has the behavior of any other value (getting off the animal from the right side). p2-p5 are almost always 0.

NativeDB Introduced: v1207
```

## Parameters
* **rider**:
* **taskFlag**:
* **p2**:
* **p3**:
* **p4**:
* **p5**:
