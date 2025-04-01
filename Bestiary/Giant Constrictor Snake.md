# Giant Constrictor Snake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Constrictor Snake | Beast | 2 | 60 (8d12 + 8) | 12 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 4 | - | - |
| Constrict | 2d8 + 4 | 14 | - |


**Multiattack.** The snake makes one Bite attack and uses Constrict.

**Bite.** {@atkr m} {@hit 6}, reach 10 ft. {@h}11 ({@damage 2d6 + 4}) Piercing damage.

**Constrict.** {@actSave str} {@dc 14}, one Large or smaller creature the snake can see within 10 feet. {@actSaveFail} 13 ({@damage 2d8 + 4}) Bludgeoning damage, and the target has the {@condition Grappled|XPHB} condition (escape {@dc 14}).

^Tags: #monster #type_beast