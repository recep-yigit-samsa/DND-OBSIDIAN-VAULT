# Mud Mephit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mud Mephit | Elemental | 1/4 | 13 (3d6 + 3) | 11 | walk: 20 ft., fly: 20 ft., swim: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Slam | 1d6 + 1 | - | - |
| Mud Breath {@recharge} | - | 11 | - |


**Slam.** {@atkr m} {@hit 3}, reach 5 ft. {@h}4 ({@damage 1d6 + 1}) Bludgeoning damage.

**Mud Breath {@recharge}.** {@actSave dex} {@dc 11}, one creature the mephit can see within 15 feet. {@actSaveFail} The target has the {@condition Restrained|XPHB} condition until the end of the mephit's next turn.

^Tags: #monster #type_elemental