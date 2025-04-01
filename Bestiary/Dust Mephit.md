# Dust Mephit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dust Mephit | Elemental | 1/2 | 17 (5d6) | 12 | walk: 30 ft., fly: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Claw | 1d4 + 2 | - | - |
| Blinding Breath {@recharge} | - | 10 | - |


**Claw.** {@atkr m} {@hit 4}, reach 5 ft. {@h}4 ({@damage 1d4 + 2}) Slashing damage.

**Blinding Breath {@recharge}.** {@actSave dex} {@dc 10}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has the {@condition Blinded|XPHB} condition until the end of the mephit's next turn.

^Tags: #monster #type_elemental