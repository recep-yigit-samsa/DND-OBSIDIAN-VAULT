# Young Silver Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Silver Dragon | Unknown | 9 | 168 (16d10 + 80) | 18 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 6 | - | - |
| Cold Breath {@recharge 5} | 11d8 | 17 | Half Damage ✅ |
| Paralyzing Breath | - | 17 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Paralyzing Breath.

**Rend.** {@atkr m} {@hit 10}, reach 10 ft. {@h}15 ({@damage 2d8 + 6}) Slashing damage.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 17}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 49 ({@damage 11d8}) Cold damage. {@actSaveSuccess} Half damage.

**Paralyzing Breath.** {@actSave con} {@dc 17}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail 1} The target has the {@condition Incapacitated|XPHB} condition until the end of its next turn, when it repeats the save. {@actSaveFail 2} The target has the {@condition Paralyzed|XPHB} condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_unknown