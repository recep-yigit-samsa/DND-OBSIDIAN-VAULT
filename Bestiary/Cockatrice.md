# Cockatrice

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cockatrice | Monstrosity | 1/2 | 22 (5d6 + 5) | 11 | walk: 20 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Petrifying Bite | 1d4 + 1 | 11 | - |


**Petrifying Bite.** {@atkr m} {@hit 3}, reach 5 ft. {@h}3 ({@damage 1d4 + 1}) Piercing damage. If the target is a creature, it is subjected to the following effect. {@actSave con} {@dc 11}. {@actSaveFail 1} The target has the {@condition Restrained|XPHB} condition. The target repeats the save at the end of its next turn if it is still {@condition Restrained|XPHB}, ending the effect on itself on a success. {@actSaveFail 2} The target has the {@condition Petrified|XPHB} condition, instead of the {@condition Restrained|XPHB} condition, for 24 hours.

^Tags: #monster #type_monstrosity