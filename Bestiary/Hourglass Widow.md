# Hourglass Widow

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hourglass Widow | Undead | 20 | 187 (22d8 + 88) | 14, 18 | walk: 30 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Disintegrating Touch | 3d6 + 6 | 20 | - |
| Withering Gaze | 6d6 | - | - |


**Multiattack.** The widow uses disintegrating touch and withering gaze.

**Disintegrating Touch.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}16 ({@damage 3d6 + 6}) force damage and the target must succeed on a {@dc 20} Constitution saving throw or have their speed decreased by 15 feet for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The effects are cumulative.

**Withering Gaze.** A creature within 30 feet that the widow can see suffers 21 ({@damage 6d6}) necrotic damage.

^Tags: #monster #type_undead