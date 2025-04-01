# Cloud Giant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cloud Giant | Giant | 9 | 200 (16d12 + 96) | 14 | walk: 40 ft., fly: {'number': 20, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Thunderous Mace | 3d8 + 8 + 2d6 | - | - |
| Thundercloud | 3d6 + 8 | - | - |


**Multiattack.** The giant makes two attacks, using Thunderous Mace or Thundercloud in any combination. It can replace one attack with a use of Spellcasting to cast {@spell Fog Cloud|XPHB}.

**Thunderous Mace.** {@atkr m} {@hit 12}, reach 10 ft. {@h}21 ({@damage 3d8 + 8}) Bludgeoning damage plus 7 ({@damage 2d6}) Thunder damage.

**Thundercloud.** {@atkr r} {@hit 12}, range 240 ft. {@h}18 ({@damage 3d6 + 8}) Thunder damage, and the target has the {@condition Incapacitated|XPHB} condition until the end of its next turn.

^Tags: #monster #type_giant