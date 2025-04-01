# Cairnwight

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cairnwight | Undead | 9 | 138 (12d12 + 60) | 19 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 3d10 + 6 | - | - |
| Rock | 3d8 + 6 | 17 | - |
| Petrifying Touch {@recharge 5} | 4d12 | 17 | - |


**Multiattack.** The cairnwight makes two Slam attacks or two Rock attacks, and it uses its Petrifying Touch if available.

**Slam.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}22 ({@damage 3d10 + 6}) bludgeoning damage.

**Rock.** {@atk rw} {@hit 10} to hit, range 60/240 ft., one target. {@h}19 ({@damage 3d8 + 6}) bludgeoning damage, and the target must succeed on a {@dc 17} Strength saving throw or have the {@condition prone} condition.

**Petrifying Touch {@recharge 5}.** The cairnwight touches one creature it can see within 10 feet of itself. The target must succeed on a {@dc 17} Constitution saving throw or take 26 ({@damage 4d12}) force damage and have the {@condition restrained} condition as it begins to turn to stone. The affected target must repeat the saving throw at the end of its next turn. On a successful save, the effect ends on the target. On a failed save, the target has the {@condition petrified} condition instead of the {@condition restrained} condition.

^Tags: #monster #type_undead