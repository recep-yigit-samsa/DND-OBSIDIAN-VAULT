# Adult Black Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Black Dragon | Unknown | {'cr': '14', 'xpLair': 13000} | 195 (17d12 + 85) | 19 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d6 + 6 + 1d8 | - | - |
| Acid Breath {@recharge 5} | 12d8 | 18 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Melf's Acid Arrow|XPHB} (level 3 version).

**Rend.** {@atkr m} {@hit 11}, reach 10 ft. {@h}13 ({@damage 2d6 + 6}) Slashing damage plus 4 ({@damage 1d8}) Acid damage.

**Acid Breath {@recharge 5}.** {@actSave dex} {@dc 18}, each creature in a 60-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 54 ({@damage 12d8}) Acid damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown