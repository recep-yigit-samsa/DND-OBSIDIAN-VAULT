# Gelatinous Cube

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gelatinous Cube | Ooze | 2 | 63 (6d10 + 30) | 6 | walk: 15 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Pseudopod | 3d6 + 2 | - | - |
| Engulf | 3d6 + 3d6 | 12 | Half Damage ✅ |


**Pseudopod.** {@atkr m} {@hit 4}, reach 5 ft. {@h}12 ({@damage 3d6 + 2}) Acid damage.

**Engulf.** The cube moves up to its {@variantrule Speed|XPHB} without provoking Opportunity Attacks. The cube can move through the spaces of Large or smaller creatures if it has room inside itself to contain them (see the Ooze {@variantrule Cube [Area of Effect]|XPHB|Cube} trait). {@actSave dex} {@dc 12}, each creature whose space the cube enters for the first time during this move. {@actSaveFail} 10 ({@damage 3d6}) Acid damage, and the target is engulfed. An engulfed target is suffocating, can't cast spells with a Verbal component, has the {@condition Restrained|XPHB} condition, and takes 10 ({@damage 3d6}) Acid damage at the start of each of the cube's turns. When the cube moves, the engulfed target moves with it. An engulfed target can try to escape by taking an action to make a {@dc 12} Strength ({@skill Athletics|XPHB}) check. On a successful check, the target escapes and enters the nearest unoccupied space. {@actSaveSuccess} Half damage, and the target moves to an unoccupied space within 5 feet of the cube. If there is no unoccupied space, the target fails the save instead.

^Tags: #monster #type_ooze