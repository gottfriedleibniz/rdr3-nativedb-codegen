---
ns: AUDIO
aliases: ["_PLAY_AMBIENT_SPEECH1"]
---
## PLAY_PED_AMBIENT_SPEECH_NATIVE

```c
// 0x8E04FEDD28D42462 0x5C57B85D
BOOL PLAY_PED_AMBIENT_SPEECH_NATIVE(Ped ped, Any* params);
```

```
struct ScriptedSpeechParams
{
	const char* speechName;
	const char* voiceName;
	alignas(8) int v3;
	alignas(8) Hash speechParamHash;
	alignas(8) Entity entity;
	alignas(8) BOOL v6;
	alignas(8) int v7;
	alignas(8) int v8;
};

static_assert(sizeof(ScriptedSpeechParams) == 0x40, "incorrect ScriptedSpeechParams size");


Example:

ScriptedSpeechParams params{"RE_PH_RHD_V3_AGGRO", "0405_U_M_M_RhdSheriff_01", 1, 0x67F3AB43, 0, true, 1, 1};
_PLAY_AMBIENT_SPEECH1(PLAYER_PED_ID(), (Any*)&params);

Old name: _PLAY_AMBIENT_SPEECH1
```

## Parameters
* **ped**:
* **params**:
