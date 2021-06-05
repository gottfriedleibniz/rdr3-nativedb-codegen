---
ns: WEAPON
aliases: ["_GIVE_WEAPON_TO_PED_2"]
---
## GIVE_WEAPON_TO_PED

```c
// 0x5E3BDDBCB83F3D84
Hash GIVE_WEAPON_TO_PED(Ped ped, Hash weaponHash, int ammoCount, BOOL bForceInHand, BOOL bForceInHolster, int attachPoint, BOOL bAllowMultipleCopies, float p7, float p8, Hash addReason, BOOL bIgnoreUnlocks, float p11, BOOL p12);
```

Gives the ped the weapon.
For a list of weapon groups, here is a weapons enum by Mooshe with all weapon-related hashes: https://pastebin.com/n72eW6zd
attachPoint: https://alloc8or.re/rdr3/doc/enums/eWeaponAttachPoint.txt
addReason: https://alloc8or.re/rdr3/doc/enums/eAddItemReason.txt

```
NativeDB Introduced: v1207
```

## Parameters
* **ped**:
* **weaponHash**:
* **ammoCount**:
* **bForceInHand**:
* **bForceInHolster**:
* **attachPoint**:
* **bAllowMultipleCopies**:
* **p7**:
* **p8**:
* **addReason**:
* **bIgnoreUnlocks**:
* **p11**:
* **p12**:
