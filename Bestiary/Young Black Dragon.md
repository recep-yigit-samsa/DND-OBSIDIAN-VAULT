# Young Black Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Black Dragon | Unknown | 7 | 127 (15d10 + 45) | 18 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d4 + 4 + 1d6 | - | - |
| Acid Breath {@recharge 5} | 14d6 | 14 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atkr m} {@hit 7}, reach 10 ft. {@h}9 ({@damage 2d4 + 4}) Slashing damage plus 3 ({@damage 1d6}) Acid damage.

**Acid Breath {@recharge 5}.** {@actSave dex} {@dc 14}, each creature in a 30-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 49 ({@damage 14d6}) Acid damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown