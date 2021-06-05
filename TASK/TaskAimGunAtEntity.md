---
ns: TASK
---
## TASK_AIM_GUN_AT_ENTITY

```c
// 0x9B53BB6E8943AF53 0xBE32B3B6
void TASK_AIM_GUN_AT_ENTITY(Ped ped, Entity targetEntity, int duration, BOOL p3, int p4);
```

duration: the amount of time in milliseconds to do the task.  -1 will keep the task going until either another task is applied, or CLEAR_ALL_TASKS() is called with the ped

```
NativeDB Introduced: v1207
```

## Parameters
* **ped**:
* **targetEntity**:
* **duration**:
* **p3**:
* **p4**:
