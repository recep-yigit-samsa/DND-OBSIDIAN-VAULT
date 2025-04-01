# Silver Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Silver Dragon Wyrmling | Unknown | 2 | 45 (6d8 + 18) | 17 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d10 + 4 | - | - |
| Cold Breath {@recharge 5} | 4d8 | 13 | Half Damage ✅ |
| Paralyzing Breath | - | 13 | - |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 6}, reach 5 ft. {@h}9 ({@damage 1d10 + 4}) Piercing damage.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 13}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 18 ({@damage 4d8}) Cold damage. {@actSaveSuccess} Half damage.

**Paralyzing Breath.** {@actSave con} {@dc 13}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail 1} The target has the {@condition Incapacitated|XPHB} condition until the end of its next turn, when it repeats the save. {@actSaveFail 2} The target has the {@condition Paralyzed|XPHB} condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_unknown