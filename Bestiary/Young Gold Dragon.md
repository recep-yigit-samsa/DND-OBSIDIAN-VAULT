# Young Gold Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Gold Dragon | Unknown | 10 | 178 (17d10 + 85) | 18 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 6 | - | - |
| Fire Breath {@recharge 5} | 10d10 | 17 | Half Damage ✅ |
| Weakening Breath | - | 17 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Weakening Breath.

**Rend.** {@atkr m} {@hit 10}, reach 10 ft. {@h}17 ({@damage 2d10 + 6}) Slashing damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 17}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 55 ({@damage 10d10}) Fire damage. {@actSaveSuccess} Half damage.

**Weakening Breath.** {@actSave str} {@dc 17}, each creature that isn't currently affected by this breath in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has {@variantrule Disadvantage|XPHB} on Strength-based {@variantrule D20 Test|XPHB|D20 Tests} and subtracts 3 ({@dice 1d6}) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_unknown