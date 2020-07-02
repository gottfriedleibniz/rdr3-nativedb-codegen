---
ns: MAP
aliases: ["0x9CB1A1623062F402"]
---
## _SET_BLIP_NAME_FROM_PLAYER_STRING

```c
// 0x9CB1A1623062F402
void _SET_BLIP_NAME_FROM_PLAYER_STRING(Blip blip, char* playerString);
```

```
Example:
const char* playerString = _CREATE_VAR_STRING(10, "PLAYER_STRING", GET_PLAYER_NAME(PLAYER_ID()));
_SET_BLIP_NAME_FROM_PLAYER_STRING(blip, playerString);
```

## Parameters
* **blip**:
* **playerString**:
