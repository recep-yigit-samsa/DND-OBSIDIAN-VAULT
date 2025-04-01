# Piercer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Piercer | Aberration | 1/2 | 22 (3d8 + 9) | 15 | walk: 5 ft., climb: 15 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d8 + 1 | - | - |
| Drop | 3d6 | 11 | - |


**Bite.** {@atkr m} {@hit 3}, reach 5 ft. {@h}5 ({@damage 1d8 + 1}) Piercing damage.

**Drop.** The piercer falls. {@actSave dex} {@dc 11}, one creature directly underneath the piercer. {@actSaveFail} 10 ({@damage 3d6}) Piercing damage. {@actSaveSuccessOrFail} The piercer reduces any damage it takes from the fall by 20.

^Tags: #monster #type_aberration