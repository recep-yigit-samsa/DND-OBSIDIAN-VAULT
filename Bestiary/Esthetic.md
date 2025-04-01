# Esthetic

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Esthetic | Aberration | 12 | 217 (14d20 + 70) | 14 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 3d6 + 7 + 4d8 | 17 | - |


**Multiattack.** The esthetic makes two Tentacle attacks.

**Tentacle.** {@atk mw} {@hit 11} to hit, reach 30 ft., one target. {@h}17 ({@damage 3d6 + 7}) force damage, and if the target is a creature, it is {@condition grappled} (escape {@dc 17}). Until this grapple ends, the creature takes 18 ({@damage 4d8}) acid damage at the start of each of its turns, and the esthetic can't use this tentacle against other targets. The esthetic has {@dice 1d4 × 2} tentacles, each of which can grapple one target.

^Tags: #monster #type_aberration