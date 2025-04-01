# Ancient Gold Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Gold Dragon | Unknown | {'cr': '24', 'xpLair': 75000} | 546 (28d20 + 252) | 22 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 10 + 2d8 | - | - |
| Fire Breath {@recharge 5} | 13d10 | 24 | Half Damage ✅ |
| Weakening Breath | - | 24 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast {@spell Guiding Bolt|XPHB} (level 4 version) or (B) Weakening Breath.

**Rend.** {@atkr m} {@hit 17} to hit, reach 15 ft. {@h}19 ({@damage 2d8 + 10}) Slashing damage plus 9 ({@damage 2d8}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 24}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 71 ({@damage 13d10}) Fire damage. {@actSaveSuccess} Half damage.

**Weakening Breath.** {@actSave str} {@dc 24}, each creature that isn't currently affected by this breath in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has {@variantrule Disadvantage|XPHB} on Strength-based {@variantrule D20 Test|XPHB|D20 Tests} and subtracts 5 ({@dice 1d10}) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_unknown