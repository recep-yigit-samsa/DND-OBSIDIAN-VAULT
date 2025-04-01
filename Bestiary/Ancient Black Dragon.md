# Ancient Black Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Black Dragon | Unknown | {'cr': '21', 'xpLair': 41000} | 367 (21d20 + 147) | 22 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 8 + 2d8 | - | - |
| Acid Breath {@recharge 5} | 15d8 | 22 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Melf's Acid Arrow|XPHB} (level 4 version).

**Rend.** {@atkr m} {@hit 15}, reach 15 ft. {@h}17 ({@damage 2d8 + 8}) Slashing damage plus 9 ({@damage 2d8}) Acid damage.

**Acid Breath {@recharge 5}.** {@actSave dex} {@dc 22}, each creature in a 90-foot-long, 10-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 67 ({@damage 15d8}) Acid damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown