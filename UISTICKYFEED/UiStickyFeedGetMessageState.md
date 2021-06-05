---
ns: UISTICKYFEED
aliases: ["0x07954320D77F6A3D"]
---
## _UI_STICKY_FEED_GET_MESSAGE_STATE

```c
// 0x07954320D77F6A3D
int _UI_STICKY_FEED_GET_MESSAGE_STATE(int msgId);
```

Returns state of sticky feed message:
0 - INITIALIZING
1 - IN QUEUE
2 - WAITING TO SHOW
3 - ENTERING
4 - SHOWING
5 - EXITING
6 - COMPLETE
7 - COUNT

```
NativeDB Introduced: v1207
```

## Parameters
* **msgId**:
