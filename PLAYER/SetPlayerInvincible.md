---
ns: PLAYER
---
## SET_PLAYER_INVINCIBLE

```c
// 0xFEBEEBC9CBDF4B12 0xDFB9A2A2
void SET_PLAYER_INVINCIBLE(Player player, BOOL toggle);
```

```
Simply sets you as invincible (Health will not deplete).

Use 0x733A643B5B0C53C1 instead if you want Ragdoll enabled, which is equal to:
*(DWORD *)(playerPedAddress + 0x188) |= (1 << 9);

NativeDB Introduced: v1207
```

## Parameters
* **player**:
* **toggle**:
