---
ns: WEAPON
aliases: ["0xB6CFEC32E3742779"]
---
## _REMOVE_AMMO_FROM_PED_BY_TYPE

```c
// 0xB6CFEC32E3742779
void _REMOVE_AMMO_FROM_PED_BY_TYPE(Ped ped, Hash ammoHash, int amount, Hash removeReason);
```

removeReason must be REMOVE_REASON_USED, REMOVE_REASON_GIVEN, REMOVE_REASON_DROPPED or REMOVE_REASON_DEBUG, unless amount is -1
removeReason: https://alloc8or.re/rdr3/doc/enums/eRemoveItemReason.txt

```
NativeDB Introduced: v1207
```

## Parameters
* **ped**:
* **ammoHash**:
* **amount**:
* **removeReason**:
