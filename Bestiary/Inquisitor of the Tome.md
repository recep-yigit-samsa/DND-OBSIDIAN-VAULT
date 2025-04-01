# Inquisitor of the Tome

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Inquisitor of the Tome | Humanoid | 8 | 77 (14d8 + 14) | 11 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Force Bolt | 4d8 + 4 | - | - |
| Silver Longsword | 1d8 + 4 + 1d10 + 4 + 4d8 | - | - |
| Implode {@recharge 4} | 6d8 + 4 | 15 | - |


**Multiattack.** The inquisitor attacks twice.

**Force Bolt.** {@atk rs} {@hit 7} to hit, range 120 ft., one target. {@h}22 ({@damage 4d8 + 4}) force damage, and if the target is a Large or smaller creature, the inquisitor can push it up to 10 feet away.

**Silver Longsword.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d8 + 4}) slashing damage, or 9 ({@damage 1d10 + 4}) if used with two hands, plus 18 ({@damage 4d8}) force damage.

**Implode {@recharge 4}.** Each creature in a 20-foot-radius sphere centered on a point the inquisitor can see within 120 feet of it must succeed on a {@dc 15} Constitution saving throw or take 31 ({@damage 6d8 + 4}) force damage and be knocked {@condition prone} and moved to the unoccupied space closest to the sphere's center. Large and smaller objects that aren't being worn or carried in the sphere automatically take the damage and are similarly moved.

^Tags: #monster #type_humanoid