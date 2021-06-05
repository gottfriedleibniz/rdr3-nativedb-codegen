---
ns: MISC
---
## UPDATE_ONSCREEN_KEYBOARD

```c
// 0x37DF360F235A3893 0x23D0A1CE
int UPDATE_ONSCREEN_KEYBOARD();
```

Returns the current status of the onscreen keyboard, and updates the output.
Status Codes:
0 - User still editing
1 - User has finished editing
2 - User has canceled editing
3 - Keyboard isn't active

```
NativeDB Introduced: v1207
```

