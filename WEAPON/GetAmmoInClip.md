---
ns: WEAPON
---
## GET_AMMO_IN_CLIP

```c
// 0x2E1202248937775C 0x73C100C3
BOOL GET_AMMO_IN_CLIP(Ped ped, Hash weaponHash, int* ammo);
```


## Parameters
* **ped**: 
* **weaponHash**: 
* **ammo**: 

## Return value

## Example Code:

```lua
local ped = PlayerPedId() -- current PlayerPed
local weapon = GetSelectedPedWeapon(ped)
local boolean, ammo = GetAmmoInClip(ped, weapon)

print(boolean, ammo) -- return a boolean and the current ammo in the clip of your equipped weapon
```
