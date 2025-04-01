# Ancient White Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient White Dragon | Unknown | {'cr': '20', 'xpLair': 33000} | 333 (18d20 + 144) | 20 | walk: 40 ft., burrow: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 8 + 2d6 | - | - |
| Cold Breath {@recharge 5} | 14d8 | 22 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atkr m} {@hit 14}, reach 15 ft. {@h}17 ({@damage 2d8 + 8}) Slashing damage plus 7 ({@damage 2d6}) Cold damage.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 22}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 63 ({@damage 14d8}) Cold damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown