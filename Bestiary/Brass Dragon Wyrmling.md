# Brass Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Brass Dragon Wyrmling | Unknown | 1 | 22 (4d8 + 4) | 15 | walk: 30 ft., burrow: 15 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Rend | 1d10 + 2 | - | - |
| Fire Breath {@recharge 5} | 4d6 | 11 | Half Damage ✅ |
| Sleep Breath | - | 11 | - |


**Rend.** {@atkr m} {@hit 4}, reach 5 ft. {@h}7 ({@damage 1d10 + 2}) Slashing damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 11}, each creature in a 20-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 14 ({@damage 4d6}) Fire damage. {@actSaveSuccess} Half damage.

**Sleep Breath.** {@actSave con} {@dc 11}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has the {@condition Incapacitated|XPHB} condition until the end of its next turn, at which point it repeats the save. {@actSaveFail 2} The target has the {@condition Unconscious|XPHB} condition for 1 minute. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.

^Tags: #monster #type_unknown