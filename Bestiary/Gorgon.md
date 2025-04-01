# Gorgon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gorgon | Construct | 5 | 114 (12d10 + 48) | 19 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Gore | 2d12 + 5 | - | - |
| Petrifying Breath {@recharge 5} | - | 15 | - |


**Gore.** {@atkr m} {@hit 8}, reach 5 ft. {@h}18 ({@damage 2d12 + 5}) Piercing damage. If the target is a Large or smaller creature and the gorgon moved 20+ feet straight toward it immediately before the hit, the target has the {@condition Prone|XPHB} condition.

**Petrifying Breath {@recharge 5}.** {@actSave con} {@dc 15}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail 1} The target has the {@condition Restrained|XPHB} condition and repeats the save at the end of its next turn if it is still {@condition Restrained|XPHB}, ending the effect on itself on a success. {@actSaveFail 2} The target has the {@condition Petrified|XPHB} condition instead of the {@condition Restrained|XPHB} condition.

^Tags: #monster #type_construct