# Water Elemental

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Water Elemental | Elemental | 5 | 114 (12d10 + 48) | 14 | walk: 30 ft., swim: 90 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d8 + 4 | - | - |
| Whelm {@recharge 4} | 4d8 + 4 + 2d8 | 15 | Half Damage ✅ |


**Multiattack.** The elemental makes two Slam attacks.

**Slam.** {@atkr m} {@hit 7}, reach 5 ft. {@h}13 ({@damage 2d8 + 4}) Bludgeoning damage. If the target is a Medium or smaller creature, it has the {@condition Prone|XPHB} condition.

**Whelm {@recharge 4}.** {@actSave str} {@dc 15}, each creature in the elemental's space. {@actSaveFail} 22 ({@damage 4d8 + 4}) Bludgeoning damage. If the target is a Large or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 14}). Until the grapple ends, the target has the {@condition Restrained|XPHB} condition, is suffocating unless it can breathe water, and takes 9 ({@damage 2d8}) Bludgeoning damage at the start of each of the elemental's turns. The elemental can grapple one Large creature or up to two Medium or smaller creatures at a time with Whelm. As an action, a creature within 5 feet of the elemental can pull a creature out of it by succeeding on a {@dc 14} Strength ({@skill Athletics|XPHB}) check. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_elemental