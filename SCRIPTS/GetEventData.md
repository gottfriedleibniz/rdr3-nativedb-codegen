---
ns: SCRIPTS
---
## GET_EVENT_DATA

```c
// 0x57EC5FA4D4D6AFCA 0x4280F92F
BOOL GET_EVENT_DATA(int eventGroup, int eventIndex, Any* eventData, int eventDataSize);
```

eventGroup: 0 = SCRIPT_EVENT_QUEUE_AI (CEventGroupScriptAI), 1 = SCRIPT_EVENT_QUEUE_NETWORK (CEventGroupScriptNetwork), 2 = unk, 3 = unk, 4 = SCRIPT_EVENT_QUEUE_SCRIPT_ERRORS (CEventGroupScriptErrors)
Note: eventDataSize is NOT the size in bytes, it is the size determined by the SIZE_OF operator (RAGE Script operator, not C/C++ sizeof). That is, the size in bytes divided by 8 (script variables are always 8-byte aligned!).

```
NativeDB Introduced: v1207
```

## Parameters
* **eventGroup**:
* **eventIndex**:
* **eventData**:
* **eventDataSize**:
