# Adult Green Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Green Dragon | Unknown | {'cr': '15', 'xpLair': 15000} | 207 (18d12 + 90) | 19 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 6 + 2d6 | - | - |
| Poison Breath {@recharge 5} | 16d6 | 18 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Mind Spike|XPHB} (level 3 version).

**Rend.** {@atkr m} {@hit 11}, reach 10 ft. {@h}15 ({@damage 2d8 + 6}) Slashing damage plus 7 ({@damage 2d6}) Poison damage.

**Poison Breath {@recharge 5}.** {@actSave con} {@dc 18}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 56 ({@damage 16d6}) Poison damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown