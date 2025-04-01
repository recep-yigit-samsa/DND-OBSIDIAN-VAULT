# Green Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Green Dragon Wyrmling | Unknown | 2 | 38 (7d8 + 7) | 17 | walk: 30 ft., fly: 60 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d10 + 2 + 1d6 | - | - |
| Poison Breath {@recharge 5} | 6d6 | 11 | Half Damage ✅ |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 4}, reach 5 ft. {@h}7 ({@damage 1d10 + 2}) Slashing damage plus 3 ({@damage 1d6}) Poison damage.

**Poison Breath {@recharge 5}.** {@actSave con} {@dc 11}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 21 ({@damage 6d6}) Poison damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown