# Otyugh

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Otyugh | Aberration | 5 | 104 (11d10 + 44) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 3 | 15 | - |
| Tentacle | 2d8 + 3 | 13 | - |
| Tentacle Slam | 3d8 + 3 | 14 | Half Damage ✅ |


**Multiattack.** The otyugh makes one Bite attack and two Tentacle attacks.

**Bite.** {@atkr m} {@hit 6}, reach 5 ft. {@h}12 ({@damage 2d8 + 3}) Piercing damage, and the target has the {@condition Poisoned|XPHB} condition. Whenever the {@condition Poisoned|XPHB} target finishes a {@variantrule Long Rest|XPHB}, it is subjected to the following effect. {@actSave con} {@dc 15}. {@actSaveFail} The target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by 5 ({@dice 1d10}) and doesn't return to normal until the {@condition Poisoned|XPHB} condition ends on the target. {@actSaveSuccess} The {@condition Poisoned|XPHB} condition ends.

**Tentacle.** {@atkr m} {@hit 6}, reach 10 ft. {@h}12 ({@damage 2d8 + 3}) Piercing damage. If the target is a Medium or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 13}) from one of two tentacles.

**Tentacle Slam.** {@actSave con} {@dc 14}, each creature {@condition Grappled|XPHB} by the otyugh. {@actSaveFail} 16 ({@damage 3d8 + 3}) Bludgeoning damage, and the target has the {@condition Stunned|XPHB} condition until the start of the otyugh's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_aberration