# Hexton Modron

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hexton Modron | Construct | 13 | 209 (22d12 + 66) | 17 | walk: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pincer | 2d8 + 4 + 3d6 | 17 | - |
| Tentacle | 2d10 + 4 | 14 | - |


**Multiattack.** The hexton makes one Pincer attack and two Tentacle attacks.

**Pincer.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}13 ({@damage 2d8 + 4}) bludgeoning damage plus 10 ({@damage 3d6}) force damage. If the target is a creature, it must succeed on a {@dc 17} Constitution saving throw or have the {@condition incapacitated} condition until the end of its next turn.

**Tentacle.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage, and if the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 14}). Until this grapple ends, the hexton can't use this tentacle against other targets. The hexton has six tentacles, each of which can grapple one target.

^Tags: #monster #type_construct