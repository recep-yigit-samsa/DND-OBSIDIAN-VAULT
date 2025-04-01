# Adult White Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult White Dragon | Unknown | {'cr': '13', 'xpLair': 11500} | 200 (16d12 + 96) | 18 | walk: 40 ft., burrow: 30 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d6 + 6 + 1d8 | - | - |
| Cold Breath {@recharge 5} | 12d8 | 19 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atkr m} {@hit 11}, reach 10 ft. {@h}13 ({@damage 2d6 + 6}) Slashing damage plus 4 ({@damage 1d8}) Cold damage.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 19}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 54 ({@damage 12d8}) Cold damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown