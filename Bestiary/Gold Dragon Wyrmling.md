# Gold Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gold Dragon Wyrmling | Unknown | 3 | 60 (8d8 + 24) | 17 | walk: 30 ft., fly: 60 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d10 + 4 | - | - |
| Fire Breath {@recharge 5} | 4d10 | 13 | Half Damage ✅ |
| Weakening Breath | - | 13 | - |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 6}, reach 5 ft. {@h}9 ({@damage 1d10 + 4}) Slashing damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 13}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 22 ({@damage 4d10}) Fire damage. {@actSaveSuccess} Half damage.

**Weakening Breath.** {@actSave str} {@dc 13}, each creature that isn't currently affected by this breath in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has {@variantrule Disadvantage|XPHB} on Strength-based {@variantrule D20 Test|XPHB|D20 Tests} and subtracts 2 ({@dice 1d4}) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_unknown