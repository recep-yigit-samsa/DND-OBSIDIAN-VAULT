# White Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| White Dragon Wyrmling | Unknown | 2 | 32 (5d8 + 10) | 16 | walk: 30 ft., burrow: 15 ft., fly: 60 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d8 + 2 + 1d4 | - | - |
| Cold Breath {@recharge 5} | 5d8 | 12 | Half Damage ✅ |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 4}, reach 5 ft. {@h}6 ({@damage 1d8 + 2}) Slashing damage plus 2 ({@damage 1d4}) Cold damage.

**Cold Breath {@recharge 5}.** {@actSave con} {@dc 12}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 22 ({@damage 5d8}) Cold damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown