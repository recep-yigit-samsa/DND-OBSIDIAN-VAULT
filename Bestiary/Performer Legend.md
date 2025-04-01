# Performer Legend

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Performer Legend | Humanoid | 10 | 162 (25d8 + 50) | 20 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bejeweled Baton | 2d4 + 5 + 3d6 | - | - |
| Majestic Song | 4d8 + 4 | 17 | Half Damage ✅ |


**Multiattack.** The performer makes three Bejeweled Baton attacks.

**Bejeweled Baton.** {@atkr m} {@hit 9}, reach 5 ft. {@h}10 ({@damage 2d4 + 5}) Bludgeoning damage plus 10 ({@damage 3d6}) Psychic damage.

**Majestic Song.** {@actSave wis} {@dc 17}, each creature in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point within 120 feet. {@actSaveFail} 22 ({@damage 4d8 + 4}) Psychic damage, and the target has the {@condition Charmed|XPHB} or {@condition Frightened|XPHB} condition (performer's choice) until the end of the performer's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_humanoid