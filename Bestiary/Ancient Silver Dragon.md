# Ancient Silver Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Silver Dragon | Unknown | {'cr': '23', 'xpLair': 62000} | 468 (24d20 + 216) | 22 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 10 + 2d8 | - | - |
| Cold Breath {@recharge 5} | 15d8 | 24 | Half Damage ✅ |
| Paralyzing Breath | - | 24 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast {@spell Ice Knife|XPHB} (level 2 version).

**Rend.** {@atkr m} {@hit 17}, reach 15 ft. {@h}19 ({@damage 2d8 + 10}) Slashing damage plus 9 ({@damage 2d8}) Cold damage.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 24}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 67 ({@damage 15d8}) Cold damage. {@actSaveSuccess} Half damage.

**Paralyzing Breath.** {@actSave con} {@dc 24}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail 1} The target has the {@condition Incapacitated|XPHB} condition until the end of its next turn, when it repeats the save. {@actSaveFail 2} The target has the {@condition Paralyzed|XPHB} condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_unknown