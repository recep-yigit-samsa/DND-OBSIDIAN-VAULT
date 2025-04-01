# Ancient Blue Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Blue Dragon | Unknown | {'cr': '23', 'xpLair': 62000} | 481 (26d20 + 208) | 22 | walk: 40 ft., burrow: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 9 + 2d10 | - | - |
| Lightning Breath {@recharge 5} | 16d10 | 23 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Shatter|XPHB} (level 3 version).

**Rend.** {@atkr m} {@hit 16}, reach 15 ft. {@h}18 ({@damage 2d8 + 9}) Slashing damage plus 11 ({@damage 2d10}) Lightning damage.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 23}, each creature in a 120-foot-long, 10-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 88 ({@damage 16d10}) Lightning damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown