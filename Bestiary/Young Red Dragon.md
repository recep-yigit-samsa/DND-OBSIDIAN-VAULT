# Young Red Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Red Dragon | Unknown | 10 | 178 (17d10 + 85) | 18 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d6 + 6 + 1d6 | - | - |
| Fire Breath {@recharge 5} | 16d6 | 17 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atkr m} {@hit 10}, reach 10 ft. {@h}13 ({@damage 2d6 + 6}) Slashing damage plus 3 ({@damage 1d6}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 17}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 56 ({@damage 16d6}) Fire damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown