# Adult Silver Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Silver Dragon | Unknown | {'cr': '16', 'xpLair': 18000} | 216 (16d12 + 112) | 19 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 8 + 1d8 | - | - |
| Cold Breath {@recharge 5} | 12d8 | 20 | Half Damage ✅ |
| Paralyzing Breath | - | 20 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast {@spell Ice Knife|XPHB}.

**Rend.** {@atkr m} {@hit 13}, reach 10 ft. {@h}17 ({@damage 2d8 + 8}) Slashing damage plus 4 ({@damage 1d8}) Cold damage.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 20}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 54 ({@damage 12d8}) Cold damage. {@actSaveSuccess} Half damage.

**Paralyzing Breath.** {@actSave con} {@dc 20}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail 1} The target has the {@condition Incapacitated|XPHB} condition until the end of its next turn, when it repeats the save. {@actSaveFail 2} The target has the {@condition Paralyzed|XPHB} condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_unknown