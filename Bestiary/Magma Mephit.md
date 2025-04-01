# Magma Mephit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Magma Mephit | Elemental | 1/2 | 18 (4d6 + 4) | 11 | walk: 30 ft., fly: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Claw | 1d4 + 1 + 1d6 | - | - |
| Fire Breath {@recharge} | 2d6 | 11 | Half Damage ✅ |


**Claw.** {@atkr m} {@hit 3}, reach 5 ft. {@h}3 ({@damage 1d4 + 1}) Slashing damage plus 3 ({@damage 1d6}) Fire damage.

**Fire Breath {@recharge}.** {@actSave dex} {@dc 11}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 7 ({@damage 2d6}) Fire damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_elemental