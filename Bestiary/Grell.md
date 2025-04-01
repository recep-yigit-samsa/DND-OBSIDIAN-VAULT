# Grell

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Grell | Aberration | 3 | 55 (10d8 + 10) | 12 | walk: 10 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Beak | 2d8 + 2 | - | - |
| Paralyzing Tentacles | 1d10 + 2 | 12 | - |


**Multiattack.** The grell makes one Beak attack and one Paralyzing Tentacles attack.

**Beak.** {@atkr m} {@hit 4}, reach 5 ft. {@h}11 ({@damage 2d8 + 2}) Piercing damage.

**Paralyzing Tentacles.** {@atkr m} {@hit 4}, reach 10 ft. {@h}7 ({@damage 1d10 + 2}) Piercing damage. If the target is a Medium or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 12}) from two of ten tentacles. The target is also subjected to the following effect. {@actSave con} {@dc 11}. {@actSaveFail} The target has the {@condition Poisoned|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. While {@condition Poisoned|XPHB}, the target has the {@condition Paralyzed|XPHB} condition.

^Tags: #monster #type_aberration