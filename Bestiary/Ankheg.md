# Ankheg

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ankheg | Monstrosity | 2 | 45 (6d10 + 12) | 14 | walk: 30 ft., burrow: 10 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d6 + 3 + 1d6 | 13 | - |
| Acid Spray {@recharge} | 4d6 | 12 | Half Damage ✅ |


**Bite.** {@atkr m} {@hit 5} (with {@variantrule Advantage|XPHB} if the target is {@condition Grappled|XPHB} by the ankheg), reach 5 ft. {@h}10 ({@damage 2d6 + 3}) Slashing damage plus 3 ({@damage 1d6}) Acid damage. If the target is a Large or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 13}).

**Acid Spray {@recharge}.** {@actSave dex} {@dc 12}, each creature in a 30-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 14 ({@damage 4d6}) Acid damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_monstrosity