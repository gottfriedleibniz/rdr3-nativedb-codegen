---
ns: CAM
---
## _CLAMP_GAMEPLAY_CAM_PITCH

```c
// 0x326C7AA308F3DF6A 0xFA3A16E7
void _CLAMP_GAMEPLAY_CAM_PITCH(float minimum, float maximum);
```

minimum: Degrees between -90f and 90f.
maximum: Degrees between -90f and 90f.
Clamps the gameplay camera's current pitch.
Eg. _CLAMP_GAMEPLAY_CAM_PITCH(0.0f, 0.0f) will set the vertical angle directly behind the player.

```
NativeDB Introduced: v1207
```

## Parameters
* **minimum**:
* **maximum**:
