---
ns: GRAPHICS
---
## SET_ARTIFICIAL_LIGHTS_STATE

```c
// 0xB2797619A7C7747B 0xAA2A0EAF
void SET_ARTIFICIAL_LIGHTS_STATE(BOOL state);
```

```
Does not affect weapons, particles, fire/explosions, flashlights or the sun.
When set to true, all emissive textures (including ped components that have light effects), street lights, building lights, vehicle lights, etc will all be turned off.

state: True turns off all artificial light sources in the map: buildings, street lights, car lights, etc. False turns them back on.
```

## Parameters
* **state**:
