# Hell Hound

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hell Hound | Fiend | 3 | 58 (9d8 + 18) | 15 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d8 + 3 + 1d6 | - | - |
| Fire Breath {@recharge 5} | 5d6 | 12 | Half Damage ✅ |


**Multiattack.** The hound makes two Bite attacks.

**Bite.** {@atkr m} {@hit 5}, reach 5 ft. {@h}7 ({@damage 1d8 + 3}) Piercing damage plus 3 ({@damage 1d6}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 12}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 17 ({@damage 5d6}) Fire damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_fiend