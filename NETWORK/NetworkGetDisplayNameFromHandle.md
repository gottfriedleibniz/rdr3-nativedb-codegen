---
ns: NETWORK
aliases: ["0x7FEE4F07C54B6B3C"]
---
## _NETWORK_GET_DISPLAY_NAME_FROM_HANDLE

```c
// 0x7FEE4F07C54B6B3C
BOOL _NETWORK_GET_DISPLAY_NAME_FROM_HANDLE(Any* netHandle, char* displayName);
```

```
Example:

char displayName[64];
if (_NETWORK_GET_DISPLAY_NAME_FROM_HANDLE(handle, displayName))
{
	// use displayName
}
```

## Parameters
* **netHandle**:
* **displayName**:
