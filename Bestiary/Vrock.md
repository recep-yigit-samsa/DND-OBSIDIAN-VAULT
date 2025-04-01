# Vrock

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vrock | Unknown | 6 | 152 (16d10 + 64) | 15 | walk: 40 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Shred | 2d6 + 3 + 3d6 | - | - |
| Spores {@recharge} | 1d10 | 15 | - |
| Stunning Screech (1/Day) | 3d6 | 15 | - |


**Multiattack.** The vrock makes two Shred attacks.

**Shred.** {@atkr m} {@hit 6}, reach 5 ft. {@h}10 ({@damage 2d6 + 3}) Piercing damage plus 10 ({@damage 3d6}) Poison damage.

**Spores {@recharge}.** {@actSave con} {@dc 15}, each creature in a 20-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the vrock. {@actSaveFail} The target has the {@condition Poisoned|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. While {@condition Poisoned|XPHB}, the target takes 5 ({@damage 1d10}) Poison damage at the start of each of its turns. Emptying a flask of Holy Water on the target ends the effect early.

**Stunning Screech (1/Day).** {@actSave con} {@dc 15}, each creature in a 20-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the vrock (demons succeed automatically). {@actSaveFail} 10 ({@damage 3d6}) Thunder damage, and the target has the {@condition Stunned|XPHB} condition until the end of the vrock's next turn.

^Tags: #monster #type_unknown