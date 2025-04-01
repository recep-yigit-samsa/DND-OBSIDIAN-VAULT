# Tree Blight

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tree Blight | Plant | 7 | 115 (10d12 + 50) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Branch | 3d6 + 6 | - | - |
| Grasping Root | 2d6 + 6 | 17 | - |


**Multiattack.** The blight makes two Branch attacks and uses Grasping Root.

**Branch.** {@atkr m} {@hit 9}, reach 15 ft. {@h}16 ({@damage 3d6 + 6}) Bludgeoning damage.

**Grasping Root.** {@actSave str} {@dc 17}, one Large or smaller creature the blight can see within 15 feet. {@actSaveFail} The target is pulled up to 10 feet straight toward the blight and has the {@condition Grappled|XPHB} condition (escape {@dc 16}) from one of six roots. Until the grapple ends, the target takes 13 ({@damage 2d6 + 6}) Bludgeoning damage at the start of each of its turns.

^Tags: #monster #type_plant