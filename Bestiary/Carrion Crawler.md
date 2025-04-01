# Carrion Crawler

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Carrion Crawler | Monstrosity | 2 | 51 (6d10 + 18) | 13 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d4 + 2 + 1d6 | - | - |
| Paralyzing Tentacles | - | 12 | - |


**Multiattack.** The carrion crawler uses Paralyzing Tentacles and makes one Bite attack.

**Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}7 ({@damage 2d4 + 2}) Piercing damage plus 3 ({@damage 1d6}) Poison damage.

**Paralyzing Tentacles.** {@actSave con} {@dc 12}, one creature the carrion crawler can see within 10 feet. {@actSaveFail} The target has the {@condition Poisoned|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. While {@condition Poisoned|XPHB}, the target has the {@condition Paralyzed|XPHB} condition.

^Tags: #monster #type_monstrosity