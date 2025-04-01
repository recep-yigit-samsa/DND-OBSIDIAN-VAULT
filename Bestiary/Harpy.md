# Harpy

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Harpy | Monstrosity | 1 | 38 (7d8 + 7) | 11 | walk: 20 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Claw | 2d4 + 1 | - | - |
| Luring Song | - | 11 | - |


**Claw.** {@atkr m} {@hit 3}, reach 5 ft. {@h}6 ({@damage 2d4 + 1}) Slashing damage.

**Luring Song.** The harpy sings a magical melody, which lasts until the harpy's {@status Concentration|XPHB} ends on it. {@actSave wis} {@dc 11}, each Humanoid and Giant in a 300-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the harpy when the song starts. {@actSaveFail} The target has the {@condition Charmed|XPHB} condition until the song ends and repeats the save at the end of each of its turns. While {@condition Charmed|XPHB}, the target has the {@condition Incapacitated|XPHB} condition and ignores the Luring Song of other harpies. If the target is more than 5 feet from the harpy, the target moves on its turn toward the harpy by the most direct route, trying to get within 5 feet of the harpy. It doesn't avoid Opportunity Attacks; however, before moving into damaging terrain (such as lava or a pit) and whenever it takes damage from a source other than the harpy, the target repeats the save. {@actSaveSuccess} The target is immune to this harpy's Luring Song for 24 hours.

^Tags: #monster #type_monstrosity