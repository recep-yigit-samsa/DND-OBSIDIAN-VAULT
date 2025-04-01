# Gibbering Mouther

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gibbering Mouther | Aberration | 2 | 52 (7d8 + 21) | 9 | walk: 20 ft., swim: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d6 | - | - |
| Blinding Spittle {@recharge 5} | 2d6 | 10 | - |


**Bite.** {@atkr m} {@hit 2}, reach 5 ft. {@h}7 ({@damage 2d6}) Piercing damage. If the target is a Medium or smaller creature, it has the {@condition Prone|XPHB} condition. The target dies if it is reduced to 0 {@variantrule Hit Points|XPHB} by this attack. Its body is then absorbed into the mouther, leaving only equipment behind.

**Blinding Spittle {@recharge 5}.** {@actSave dex} {@dc 10}, each creature in a 10-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point within 30 feet. {@actSaveFail} 7 ({@damage 2d6}) Radiant damage, and the target has the {@condition Blinded|XPHB} condition until the end of the mouther's next turn.

^Tags: #monster #type_aberration