---
ns: WEAPON
aliases: ["0xF4823C813CB8277D"]
---
## _REMOVE_AMMO_FROM_PED

```c
// 0xF4823C813CB8277D
void _REMOVE_AMMO_FROM_PED(Ped ped, Hash weaponHash, int amount, Hash removeReason);
```

removeReason must be REMOVE_REASON_USED, REMOVE_REASON_GIVEN, REMOVE_REASON_DROPPED or REMOVE_REASON_DEBUG, unless amount is -1
removeReason: https://alloc8or.re/rdr3/doc/enums/eRemoveItemReason.txt

```
NativeDB Introduced: v1207
```

## Parameters
* **ped**:
* **weaponHash**:
* **amount**:
* **removeReason**:
