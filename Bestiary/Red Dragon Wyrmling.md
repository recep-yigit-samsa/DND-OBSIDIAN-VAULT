# Red Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Red Dragon Wyrmling | Unknown | 4 | 75 (10d8 + 30) | 17 | walk: 30 ft., climb: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d10 + 4 + 1d6 | - | - |
| Fire Breath {@recharge 5} | 7d6 | 13 | Half Damage ✅ |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 6}, reach 5 ft. {@h}9 ({@damage 1d10 + 4}) Slashing damage plus 3 ({@damage 1d6}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 13}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 24 ({@damage 7d6}) Fire damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown