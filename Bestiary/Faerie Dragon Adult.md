# Faerie Dragon Adult

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Faerie Dragon Adult | Dragon | 2 | 35 (10d4 + 10) | 15 | walk: 10 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d4 + 5 + 1d6 | - | - |
| Euphoria Breath {@recharge 5} | - | 13 | - |


**Bite.** {@atkr m} {@hit 7}, reach 5 ft. {@h}7 ({@damage 1d4 + 5}) Piercing damage plus 3 ({@damage 1d6}) Psychic damage.

**Euphoria Breath {@recharge 5}.** {@actSave wis} {@dc 13}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has the {@condition Incapacitated|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. While {@condition Incapacitated|XPHB}, the target uses all its movement on each of its turns to move in a random direction.

^Tags: #monster #type_dragon