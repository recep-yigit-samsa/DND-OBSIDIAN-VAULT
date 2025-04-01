# Blob of Annihilation

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Blob of Annihilation | Unknown | 23 | 448 (23d20 + 207) | 18 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pseudopod | 3d10 + 8 | - | - |
| Engulf | 6d6 | 23 | - |
| Restraining Glob | 3d6 + 8 | 23 | Half Damage ✅ |


**Multiattack.** The blob makes two Pseudopod attacks and uses Engulf. It can replace one attack with a use of Restraining Glob.

**Pseudopod.** {@atkr m} {@hit 15}, reach 30 ft. {@h}24 ({@damage 3d10 + 8}) Force damage.

**Engulf.** The blob moves up to its {@variantrule Speed|XPHB} and can move through the spaces of Huge or smaller creatures and objects. {@actSave str} {@dc 23}, each creature or object whose space the blob enters for the first time during this move. {@actSaveFail} The target is engulfed. While engulfed, a target has {@variantrule Cover|XPHB|Total Cover} against attacks and other effects outside the blob, and when the blob moves, the engulfed target moves with it. A nonmagical object is destroyed after spending 1 minute engulfed. While engulfed, a creature takes 21 ({@damage 6d6}) Force damage at the start of each of its turns, is suffocating, has the {@condition Restrained|XPHB} condition, and repeats the save at the end of each of its turns. An engulfed creature that is reduced to 0 {@variantrule Hit Points|XPHB} dissolves into ash, which is ejected into the Astral Sea. {@actSaveSuccess} The target escapes and enters the nearest unoccupied space.

**Restraining Glob.** The blob lobs a slimy glob at one Large or smaller creature it can see within 600 feet of itself. {@actSave dex} {@dc 23}, the targeted creature. {@actSaveFail} 18 ({@damage 3d6 + 8}) Acid damage. The glob rolls the target 60 feet straight toward the blob, and the target has the {@condition Restrained|XPHB} condition until the end of its next turn, when the glob harmlessly dissolves. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_unknown