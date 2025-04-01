# Young Brass Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Brass Dragon | Unknown | 6 | 110 (13d10 + 39) | 17 | walk: 40 ft., burrow: 20 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 4 | - | - |
| Fire Breath {@recharge 5} | 11d6 | 14 | Half Damage ✅ |
| Sleep Breath | - | 14 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace two attacks with a use of Sleep Breath.

**Rend.** {@atkr m} {@hit 7}, reach 10 ft. {@h}15 ({@damage 2d10 + 4}) Slashing damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 14}, each creature in a 40-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 38 ({@damage 11d6}) Fire damage. {@actSaveSuccess} Half damage.

**Sleep Breath.** {@actSave con} {@dc 14}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has the {@condition Incapacitated|XPHB} condition until the end of its next turn, at which point it repeats the save. {@actSaveFail 2} The target has the {@condition Unconscious|XPHB} condition for 1 minute. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.

^Tags: #monster #type_unknown