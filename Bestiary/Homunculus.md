# Homunculus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Homunculus | Construct | 0 | 4 (1d4 + 2) | 13 | walk: 20 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | - | 12 | - |


**Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}1 Piercing damage, and the target is subjected to the following effect. {@actSave con} {@dc 12}. {@actSaveFail} The target has the {@condition Poisoned|XPHB} condition until the end of the homunculus's next turn. Failure by 5 or More: The target has the {@condition Poisoned|XPHB} condition for 1 minute. While {@condition Poisoned|XPHB}, the target has the {@condition Unconscious|XPHB} condition, which ends early if the target takes any damage.

^Tags: #monster #type_construct