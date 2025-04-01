# Chuul

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Chuul | Aberration | 4 | 76 (9d10 + 27) | 16 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pincer | 1d10 + 4 | 14 | - |
| Paralyzing Tentacles | - | 13 | - |


**Multiattack.** The chuul makes two Pincer attacks and uses Paralyzing Tentacles.

**Pincer.** {@atkr m} {@hit 6}, reach 10 ft. {@h}9 ({@damage 1d10 + 4}) Bludgeoning damage. If the target is a Large or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 14}) from one of two pincers.

**Paralyzing Tentacles.** {@actSave con} {@dc 13}, one creature {@condition Grappled|XPHB} by the chuul. {@actSaveFail} The target has the {@condition Poisoned|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. While {@condition Poisoned|XPHB}, the target has the {@condition Paralyzed|XPHB} condition.

^Tags: #monster #type_aberration