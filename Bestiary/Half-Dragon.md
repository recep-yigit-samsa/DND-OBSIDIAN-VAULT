# Half-Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Half-Dragon | Dragon | 5 | 105 (14d8 + 42) | 18 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d4 + 4 + 2d6 | - | - |
| Dragon's Breath {@recharge 5} | 8d6 | 14 | Half Damage ✅ |


**Multiattack.** The half-dragon makes two Claw attacks.

**Claw.** {@atkr m} {@hit 7}, reach 10 ft. {@h}6 ({@damage 1d4 + 4}) Slashing damage plus 7 ({@damage 2d6}) damage of the type chosen for the Draconic Origin trait.

**Dragon's Breath {@recharge 5}.** {@actSave dex} {@dc 14}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 28 ({@damage 8d6}) damage of the type chosen for the Draconic Origin trait. {@actSaveSuccess} Half damage.

^Tags: #monster #type_dragon