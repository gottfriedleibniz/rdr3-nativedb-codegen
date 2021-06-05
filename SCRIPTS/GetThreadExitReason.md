---
ns: SCRIPTS
aliases: ["0x54AE4FDEEFEAB77E"]
---
## _GET_THREAD_EXIT_REASON

```c
// 0x54AE4FDEEFEAB77E
int _GET_THREAD_EXIT_REASON();
```

enum eThreadExitReason
{
	THREAD_EXIT_REASON_NONE,
	THREAD_EXIT_REASON_BACKGROUND_THREAD_STOPPED,
	THREAD_EXIT_REASON_SESSION_MERGE,
	THREAD_EXIT_REASON_SCENARIO_OUT_OF_SCOPE,
	THREAD_EXIT_REASON_REQUESTED_BY_SCRIPT
};

```
NativeDB Introduced: v1207
```
