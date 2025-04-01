# Black Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Black Dragon Wyrmling | Unknown | 2 | 33 (6d8 + 6) | 17 | walk: 30 ft., fly: 60 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d6 + 2 + 1d4 | - | - |
| Acid Breath {@recharge 5} | 5d8 | 11 | Half Damage ✅ |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 4}, reach 5 ft. {@h}5 ({@damage 1d6 + 2}) Slashing damage plus 2 ({@damage 1d4}) Acid damage.

**Acid Breath {@recharge 5}.** {@actSave dex} {@dc 11}, each creature in a 15-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 22 ({@damage 5d8}) Acid damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown