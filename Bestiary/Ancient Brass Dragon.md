# Ancient Brass Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Brass Dragon | Unknown | {'cr': '20', 'xpLair': 33000} | 332 (19d20 + 133) | 20 | walk: 40 ft., burrow: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 8 + 2d6 | - | - |
| Fire Breath {@recharge 5} | 13d8 | 21 | Half Damage ✅ |
| Sleep Breath | - | 21 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Sleep Breath or (B) Spellcasting to cast {@spell Scorching Ray|XPHB} (level 3 version).

**Rend.** {@atkr m} {@hit 14}, reach 15 ft. {@h}19 ({@damage 2d10 + 8}) Slashing damage plus 7 ({@damage 2d6}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 21}, each creature in a 90-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 58 ({@damage 13d8}) Fire damage. {@actSaveSuccess} Half damage.

**Sleep Breath.** {@actSave con} {@dc 21}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has the {@condition Incapacitated|XPHB} condition until the end of its next turn, at which point it repeats the save. {@actSaveFail 2} The target has the {@condition Unconscious|XPHB} condition for 10 minutes. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.

^Tags: #monster #type_unknown