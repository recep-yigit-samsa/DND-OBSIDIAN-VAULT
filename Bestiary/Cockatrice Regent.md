# Cockatrice Regent

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cockatrice Regent | Monstrosity | 8 | 136 (16d10 + 48) | 15 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Petrifying Bite | 2d8 + 4 | 14 | - |
| Talons | 4d6 + 4 | - | - |


**Multiattack.** The cockatrice makes one Petrifying Bite attack and two Talons attacks.

**Petrifying Bite.** {@atkr m} {@hit 7}, reach 5 ft. {@h}13 ({@damage 2d8 + 4}) Piercing damage. If the target is a creature, it is subjected to the following effect. {@actSave con} {@dc 14}. {@actSaveFail 1} The target has the {@condition Restrained|XPHB} condition and repeats the save at the end of its next turn if it is still {@condition Restrained|XPHB}, ending the effect on itself on a success. {@actSaveFail 2} The target has the {@condition Petrified|XPHB} condition instead of the {@condition Restrained|XPHB} condition.

**Talons.** {@atkr m} {@hit 7}, reach 5 ft. {@h}18 ({@damage 4d6 + 4}) Slashing damage.

^Tags: #monster #type_monstrosity