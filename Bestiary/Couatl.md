# Couatl

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Couatl | Celestial | 4 | 60 (8d8 + 24) | 19 | walk: 30 ft., fly: 90 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d12 + 5 | - | - |
| Constrict | 1d6 + 5 | 15 | - |


**Bite.** {@atkr m} {@hit 7}, reach 5 ft. {@h}11 ({@damage 1d12 + 5}) Piercing damage, and the target has the {@condition Poisoned|XPHB} condition until the end of the couatl's next turn.

**Constrict.** {@actSave str} {@dc 15}, one Medium or smaller creature the couatl can see within 5 feet. {@actSaveFail} 8 ({@damage 1d6 + 5}) Bludgeoning damage. The target has the {@condition Grappled|XPHB} condition (escape {@dc 13}), and it has the {@condition Restrained|XPHB} condition until the grapple ends.

^Tags: #monster #type_celestial