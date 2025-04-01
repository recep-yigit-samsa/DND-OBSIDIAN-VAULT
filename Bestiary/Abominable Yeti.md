# Abominable Yeti

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Abominable Yeti | Monstrosity | 9 | 137 (11d12 + 66) | 15 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d6 + 7 + 2d6 | - | - |
| Ice Throw | 2d4 + 7 + 2d6 | - | - |
| Chilling Gaze | 6d6 | 18 | - |
| Cold Breath {@recharge} | 10d8 | 18 | Half Damage ✅ |


**Multiattack.** The yeti can use its Chilling Gaze and makes two attacks, using Claw or Ice Throw in any combination.

**Claw.** {@atkr m} {@hit 11}, reach 5 ft. {@h}14 ({@damage 2d6 + 7}) Slashing damage plus 7 ({@damage 2d6}) Cold damage.

**Ice Throw.** {@atkr r} {@hit 11}, range 60/240 ft. {@h}12 ({@damage 2d4 + 7}) Bludgeoning damage plus 7 ({@damage 2d6}) Cold damage.

**Chilling Gaze.** {@actSave con} {@dc 18}, one creature the yeti can see within 30 feet. {@actSaveFail} 21 ({@damage 6d6}) Cold damage, and the target has the {@condition Paralyzed|XPHB} condition until the start of the yeti's next turn unless the target has {@variantrule Immunity|XPHB} to Cold damage. {@actSaveSuccess} The target is immune to this yeti's Chilling Gaze for 1 hour.

**Cold Breath {@recharge}.** {@actSave con} {@dc 18}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 45 ({@damage 10d8}) Cold damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_monstrosity