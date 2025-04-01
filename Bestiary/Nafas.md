# Nafas

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nafas | Elemental | 23 | 350 (28d10 + 196) | 19 | walk: 30 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Storm Shamshir | 2d6 + 6 + 4d6 | - | - |
| Create Vortex | 8d8 | 22 | - |


**Multiattack.** Nafas makes three Storm Shamshir attacks and uses Create Vortex.

**Storm Shamshir.** {@atk mw} {@hit 13} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage plus 14 ({@damage 4d6}) lightning or thunder damage (Nafas's choice).

**Create Vortex.** A 10-foot-radius, 60-foot-tall cylinder of swirling cosmic dust forms on a point Nafas can see within 120 feet of him. The vortex lasts as long as Nafas maintains {@status concentration} (as if {@status concentration||concentrating} on a spell). When the vortex appears, each creature other than Nafas in the vortex's area must make a {@dc 22} Strength saving throw. On a failed save, a creature takes 36 ({@damage 8d8}) force damage and has the {@condition restrained} condition. On a successful save, a creature takes half as much damage only and moves to the nearest unoccupied space outside the vortex. On subsequent turns, Nafas can use this action to move the vortex up to 60 feet. When the vortex enters a creature's space for the first time on a turn, the creature must make the same saving throw as when the vortex first appeared. Creatures {@condition restrained} by the vortex move with it. A creature {@condition restrained} by the vortex, or another creature that can reach it, can use its action to make a {@dc 22} Strength check. On a successful check, the {@condition restrained} creature is no longer {@condition restrained} and moves to the nearest unoccupied space outside the vortex.

^Tags: #monster #type_elemental