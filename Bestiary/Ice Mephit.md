# Ice Mephit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ice Mephit | Elemental | 1/2 | 21 (6d6) | 11 | walk: 30 ft., fly: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Claw | 1d4 + 1 + 1d4 | - | - |
| Frost Breath {@recharge} | 3d4 | 10 | Half Damage ✅ |


**Claw.** {@atkr m} {@hit 3}, reach 5 ft. {@h}3 ({@damage 1d4 + 1}) Slashing damage plus 2 ({@damage 1d4}) Cold damage.

**Frost Breath {@recharge}.** {@actSave con} {@dc 10}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 7 ({@damage 3d4}) Cold damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_elemental