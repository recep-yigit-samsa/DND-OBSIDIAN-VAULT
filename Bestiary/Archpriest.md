# Archpriest

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Archpriest | Unknown | 12 | 240 (32d8 + 96) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Radiant Burst | 4d10 + 5 | - | - |
| Holy Word {@recharge 4} | 6d6 | 17 | Half Damage ✅ |


**Multiattack.** The archpriest makes three Radiant Burst attacks.

**Radiant Burst.** {@atkr m,r} {@hit 9}, reach 5 ft. or range 60 ft. {@h}27 ({@damage 4d10 + 5}) Radiant damage.

**Holy Word {@recharge 4}.** {@actSave wis} {@dc 17}, each enemy in a 20-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the archpriest. {@actSaveFail} 21 ({@damage 6d6}) Radiant damage, and the target has the {@condition Stunned|XPHB} condition until the end of the archpriest's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_unknown