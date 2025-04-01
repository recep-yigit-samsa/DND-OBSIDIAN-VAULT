# Ancient Green Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Green Dragon | Unknown | {'cr': '22', 'xpLair': 50000} | 402 (23d20 + 161) | 21 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 8 + 3d6 | - | - |
| Poison Breath {@recharge 5} | 22d6 | 22 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Mind Spike|XPHB} (level 5 version).

**Rend.** {@atkr m} {@hit 15}, reach 15 ft. {@h}17 ({@damage 2d8 + 8}) Slashing damage plus 10 ({@damage 3d6}) Poison damage.

**Poison Breath {@recharge 5}.** {@actSave con} {@dc 22}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 77 ({@damage 22d6}) Poison damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown