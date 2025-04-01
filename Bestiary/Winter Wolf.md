# Winter Wolf

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Winter Wolf | Monstrosity | 3 | 75 (10d10 + 20) | 13 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d6 + 4 | - | - |
| Cold Breath {@recharge 5} | 4d8 | 12 | Half Damage ✅ |


**Bite.** {@atkr m} {@hit 6}, reach 5 ft. {@h}11 ({@damage 2d6 + 4}) Piercing damage. If the target is a Large or smaller creature, it has the {@condition Prone|XPHB} condition.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 12}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 18 ({@damage 4d8}) Cold damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_monstrosity