# Yeti

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Yeti | Monstrosity | 3 | 51 (6d10 + 18) | 12 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d6 + 4 + 1d6 | - | - |
| Ice Throw | 1d4 + 4 + 1d4 | - | - |
| Chilling Gaze | 2d4 | 13 | - |


**Multiattack.** The yeti can use its Chilling Gaze and makes two attacks, using Claw or Ice Throw in any combination.

**Claw.** {@atkr m} {@hit 6}, reach 5 ft. {@h}7 ({@damage 1d6 + 4}) Slashing damage plus 3 ({@damage 1d6}) Cold damage.

**Ice Throw.** {@atkr r} {@hit 6}, range 30/120 ft. {@h}6 ({@damage 1d4 + 4}) Bludgeoning damage plus 2 ({@damage 1d4}) Cold damage.

**Chilling Gaze.** {@actSave con} {@dc 13}, one creature the yeti can see within 30 feet. {@actSaveFail} 5 ({@damage 2d4}) Cold damage, and the target has the {@condition Paralyzed|XPHB} condition until the start of the yeti's next turn unless the target has {@variantrule Immunity|XPHB} to Cold damage. {@actSaveSuccess} The target is immune to the Chilling Gaze of all yetis (but not abominable yetis) for 1 hour.

^Tags: #monster #type_monstrosity