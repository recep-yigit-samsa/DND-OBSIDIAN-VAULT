# Boloti

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Boloti | Fey | 1 | 45 (10d4 + 20) | 15 | walk: 20 ft., swim: {'number': 40, 'condition': '(0 ft. swim 60 ft. in vortex form)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Dagger (True Form Only) | 1d4 + 5 | - | - |
| Whirlpool (Vortex Form Only) | 2d8 | 12 | - |


**Dagger (True Form Only).** {@atk mw,rw} {@hit 7} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}7 ({@damage 1d4 + 5}) piercing damage.

**Whirlpool (Vortex Form Only).** One creature in the boloti's space must make a {@dc 12} Strength saving throw. On a failure, the target takes 9 ({@damage 2d8}) bludgeoning damage, and if it is Medium or smaller, it is {@condition grappled} (escape {@dc 12}). Until this grapple ends, the target is {@condition restrained} and unable to breathe unless it can breathe water. If the saving throw is successful, the target takes half the damage and is pushed out of the boloti's space.

^Tags: #monster #type_fey