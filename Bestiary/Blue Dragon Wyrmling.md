# Blue Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Blue Dragon Wyrmling | Unknown | 3 | 65 (10d8 + 20) | 17 | walk: 30 ft., burrow: 15 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d10 + 3 + 1d6 | - | - |
| Lightning Breath {@recharge 5} | 6d6 | 12 | Half Damage ✅ |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 5}, reach 5 ft. {@h}8 ({@damage 1d10 + 3}) Slashing damage plus 3 ({@damage 1d6}) Lightning damage.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 12}, each creature in a 30-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 21 ({@damage 6d6}) Lightning damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown