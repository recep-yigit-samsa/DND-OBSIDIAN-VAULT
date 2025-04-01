# Ancient Red Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Red Dragon | Unknown | {'cr': '24', 'xpLair': 75000} | 507 (26d20 + 234) | 22 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 10 + 3d6 | - | - |
| Fire Breath {@recharge 5} | 26d6 | 24 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Scorching Ray|XPHB} (level 3 version).

**Rend.** {@atkr m} {@hit 17}, reach 15 ft. {@h}19 ({@damage 2d8 + 10}) Slashing damage plus 10 ({@damage 3d6}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 24}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 91 ({@damage 26d6}) Fire damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown