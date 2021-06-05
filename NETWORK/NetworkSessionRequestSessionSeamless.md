---
ns: NETWORK
aliases: ["0x2989E131FDE37E97"]
---
## NETWORK_SESSION_REQUEST_SESSION_SEAMLESS

```c
// 0x2989E131FDE37E97
BOOL NETWORK_SESSION_REQUEST_SESSION_SEAMLESS(int flags, int p1, int userHash, Any* sessionRequestId);
```

Equivalent to NETWORK_REQUEST_SESSION_SEAMLESS if userHash == 0.
Otherwise it is equivalent to NETWORK_SESSION_REQUEST_SESSION_COMPETITIVE(flags, MATCHTYPE_SEAMLESS, userHash, 0, sessionRequestId);
p1 is unused

```
NativeDB Introduced: v1207
```

## Parameters
* **flags**:
* **p1**:
* **userHash**:
* **sessionRequestId**:
