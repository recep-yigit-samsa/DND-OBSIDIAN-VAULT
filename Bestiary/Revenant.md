# Revenant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Revenant | Undead | 5 | 127 (15d8 + 60) | 13 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d6 + 4 | - | - |
| Vengeful Glare | - | 15 | - |


**Multiattack.** The revenant uses Vengeful Glare and makes two Slam attacks.

**Slam.** {@atkr m} {@hit 7}, reach 5 ft. {@h}11 ({@damage 2d6 + 4}) Necrotic damage.

**Vengeful Glare.** {@actSave wis} {@dc 15}, one creature the revenant can see within 30 feet. {@actSaveFail} The target has the {@condition Frightened|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. If the {@condition Frightened|XPHB} target is cursed by the revenant (see Vow of Revenge), the target also has the {@condition Paralyzed|XPHB} condition for the duration.

^Tags: #monster #type_undead