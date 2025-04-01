# Adult Gold Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Gold Dragon | Unknown | {'cr': '17', 'xpLair': 20000} | 243 (18d12 + 126) | 19 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 8 + 1d8 | - | - |
| Fire Breath {@recharge 5} | 12d10 | 21 | Half Damage ✅ |
| Weakening Breath | - | 21 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast {@spell Guiding Bolt|XPHB} (level 2 version) or (B) Weakening Breath.

**Rend.** {@atkr m} {@hit 14}, reach 10 ft. {@h}17 ({@damage 2d8 + 8}) Slashing damage plus 4 ({@damage 1d8}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 21}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 66 ({@damage 12d10}) Fire damage. {@actSaveSuccess} Half damage.

**Weakening Breath.** {@actSave str} {@dc 21}, each creature that isn't currently affected by this breath in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has {@variantrule Disadvantage|XPHB} on Strength-based {@variantrule D20 Test|XPHB|D20 Tests} and subtracts 3 ({@dice 1d6}) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_unknown