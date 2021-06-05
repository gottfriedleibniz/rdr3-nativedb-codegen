---
ns: INVENTORY
aliases: ["0x13D234A2A3F66E63"]
---
## _INVENTORY_GET_INVENTORY_ID_FROM_PED

```c
// 0x13D234A2A3F66E63
int _INVENTORY_GET_INVENTORY_ID_FROM_PED(Ped ped);
```

Returns a unique inventory ID for this ped.
For the local player ped, it is an eInventories value (https://alloc8or.re/rdr3/doc/enums/eInventories.txt).
For other peds, it is the inventory address casted to unsigned int.

```
NativeDB Introduced: v1207
```

## Parameters
* **ped**:
