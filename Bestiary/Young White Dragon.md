# Young White Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young White Dragon | Unknown | 6 | 123 (13d10 + 52) | 17 | walk: 40 ft., burrow: 20 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d4 + 4 + 1d4 | - | - |
| Cold Breath {@recharge 5} | 9d8 | 15 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atkr m} {@hit 7}, reach 10 ft. {@h}9 ({@damage 2d4 + 4}) Slashing damage plus 2 ({@damage 1d4}) Cold damage.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 15}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 40 ({@damage 9d8}) Cold damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown