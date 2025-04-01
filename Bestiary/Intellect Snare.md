# Intellect Snare

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Intellect Snare | Aberration | 8 | 99 (18d6 + 36) | 14 | walk: 0 ft., fly: {'number': 45, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 1d8 + 6 | 17 | - |


**Multiattack.** The intellect snare makes two Tentacle attacks.

**Tentacle.** {@atk mw} {@hit 9} to hit, reach 15 ft., one target. {@h}10 ({@damage 1d8 + 6}) force damage, and if the target is a Medium or smaller creature, the target has the {@condition grappled} condition (escape {@dc 17}).

^Tags: #monster #type_aberration