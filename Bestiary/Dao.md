# Dao

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dao | Unknown | 11 | 200 (16d10 + 112) | 18 | walk: 30 ft., burrow: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Earthen Maul | 4d6 + 6 | - | - |
| Earth Burst | 2d8 + 6 + 3d6 | 16 | - |


**Multiattack.** The dao makes three Earthen Maul attacks or two Earth Burst attacks.

**Earthen Maul.** {@atkr m} {@hit 10}, reach 5 ft. {@h}20 ({@damage 4d6 + 6}) Bludgeoning damage. If the target is a Large or smaller creature, it has the {@condition Prone|XPHB} condition.

**Earth Burst.** {@atkr r} {@hit 10}, range 120 ft. {@h}15 ({@damage 2d8 + 6}) Bludgeoning damage. {@hom}Earth explodes from the target's space, creating the following effect. {@actSave dex} {@dc 16}, each creature in a 10-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from and including the target. {@actSaveFail} 10 ({@damage 3d6}) Thunder damage.

^Tags: #monster #type_unknown