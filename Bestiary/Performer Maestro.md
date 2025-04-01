# Performer Maestro

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Performer Maestro | Humanoid | 6 | 110 (17d8 + 34) | 18 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rapier | 1d8 + 4 + 2d6 | - | - |
| Beguiling Song | 3d10 + 4 | 15 | Half Damage ✅ |


**Multiattack.** The performer makes three Rapier attacks.

**Rapier.** {@atkr m} {@hit 7}, reach 5 ft. {@h}8 ({@damage 1d8 + 4}) Piercing damage plus 7 ({@damage 2d6}) Psychic damage.

**Beguiling Song.** {@actSave wis} {@dc 15}, each creature in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point within 120 feet. {@actSaveFail} 20 ({@damage 3d10 + 4}) Psychic damage, and the target has the {@condition Charmed|XPHB} condition until the end of the performer's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_humanoid