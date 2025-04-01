# Living Bigby's Hand

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Living Bigby's Hand | Construct | 4 | 52 (5d10 + 25) | 20 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Force Fist | 4d8 + 8 | - | - |
| Grasping Hand | 2d6 + 8 | 15 | - |


**Force Fist.** {@atk ms} {@hit 10} to hit, reach 5 ft., one target. {@h}26 ({@damage 4d8 + 8}) force damage. If the target is a Large or smaller creature, the living spell can move it up to 5 feet and move with it, without provoking opportunity attacks.

**Grasping Hand.** The living spell attempts to grab a Huge or smaller creature within 5 feet of it. The target must succeed on a {@dc 15} Dexterity saving throw or be {@condition grappled} (escape {@dc 15}). Until the grapple ends, the target takes 15 ({@damage 2d6 + 8}) bludgeoning damage at the start of each of its turns. The living spell can grapple only one creature at a time and can't use Force Fist until the grapple ends.

^Tags: #monster #type_construct