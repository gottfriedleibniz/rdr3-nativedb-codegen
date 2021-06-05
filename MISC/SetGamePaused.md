---
ns: MISC
---
## SET_GAME_PAUSED

```c
// 0xFAEC088D28B1DE4A 0x8230FF6C
void SET_GAME_PAUSED(BOOL toggle);
```

Make sure to call this from the correct thread if you're using multiple threads because all other threads except the one which is calling SET_GAME_PAUSED will be paused.

```
NativeDB Introduced: v1207
```

## Parameters
* **toggle**:
