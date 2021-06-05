---
ns: VOLUME
aliases: ["0xB33A604345F58202"]
---
## GET_VOLUME_LOCK_REQUEST_STATUS

```c
// 0xB33A604345F58202
int GET_VOLUME_LOCK_REQUEST_STATUS(int volLockRequestId);
```

enum eVolumeLockRequestStatus
{
	VOLUME_LOCK_REQUEST_STATUS_INVALID,
	VOLUME_LOCK_REQUEST_STATUS_READY,
	VOLUME_LOCK_REQUEST_STATUS_IN_PROGRESS,
	VOLUME_LOCK_REQUEST_STATUS_SUCCEEDED,
	VOLUME_LOCK_REQUEST_STATUS_FAILED
};

```
NativeDB Introduced: v1207
```

## Parameters
* **volLockRequestId**: