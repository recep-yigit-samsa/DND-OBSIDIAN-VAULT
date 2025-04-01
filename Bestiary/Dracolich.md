# Dracolich

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dracolich | Undead | {'cr': '17', 'xpLair': 20000} | 225 (18d12 + 108) | 20 | walk: 40 ft., burrow: 30 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 7 + 1d8 | - | - |
| Necrotic Breath {@recharge 5} | 8d12 | 20 | Half Damage ✅ |


**Multiattack.** The dracolich makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Ray of Sickness|XPHB} (level 2 version).

**Rend.** {@atkr m} {@hit 13}, reach 10 ft. {@h}18 ({@damage 2d10 + 7}) Slashing damage plus 4 ({@damage 1d8}) Necrotic damage.

**Necrotic Breath {@recharge 5}.** {@actSave con} {@dc 20}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 52 ({@damage 8d12}) Necrotic damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_undead