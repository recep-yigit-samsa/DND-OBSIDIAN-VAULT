# Steam Mephit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Steam Mephit | Elemental | 1/4 | 17 (5d6) | 10 | walk: 30 ft., fly: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Claw | 1d4 + 1d4 | - | - |
| Steam Breath {@recharge} | 2d4 | 10 | Half Damage ✅ |


**Claw.** {@atkr m} {@hit 2}, reach 5 ft. {@h}2 ({@damage 1d4}) Slashing damage plus 2 ({@damage 1d4}) Fire damage.

**Steam Breath {@recharge}.** {@actSave con} {@dc 10}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 5 ({@damage 2d4}) Fire damage, and the target's {@variantrule Speed|XPHB} decreases by 10 feet until the end of the mephit's next turn. {@actSaveSuccess} Half damage only. {@actSaveSuccessOrFail} Being underwater doesn't grant {@variantrule Resistance|XPHB} to this Fire damage.

^Tags: #monster #type_elemental