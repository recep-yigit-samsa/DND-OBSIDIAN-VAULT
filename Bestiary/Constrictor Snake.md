# Constrictor Snake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Constrictor Snake | Beast | 1/4 | 13 (2d10 + 2) | 13 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d8 + 2 | - | - |
| Constrict | 3d4 | 12 | - |


**Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}6 ({@damage 1d8 + 2}) Piercing damage.

**Constrict.** {@actSave str} {@dc 12}, one Medium or smaller creature the snake can see within 5 feet. {@actSaveFail} 7 ({@damage 3d4}) Bludgeoning damage, and the target has the {@condition Grappled|XPHB} condition (escape {@dc 12}).

^Tags: #monster #type_beast