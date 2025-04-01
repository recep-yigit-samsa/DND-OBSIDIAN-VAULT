# Death Kiss

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Death Kiss | Aberration | 10 | 161 (17d10 + 68) | 16 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 3d6 + 4 | 14 | - |
| Blood Drain | 4d10 | 16 | - |


**Multiattack.** The death kiss makes three tentacle attacks. Up to three of these attacks can be replaced by Blood Drain, one replacement per tentacle grappling a creature

**Tentacle.** {@atk mw} {@hit 8} to hit, reach 20 ft., one target. {@h}14 ({@damage 3d6 + 4}) piercing damage, and the target is {@condition grappled} (escape {@dc 14}) if it is a Huge or smaller creature. Until this grapple ends, the target is {@condition restrained}, and the death kiss can't use the same tentacle on another target. The death kiss has ten tentacles.

**Blood Drain.** One creature {@condition grappled} by a tentacle of the death kiss must make a {@dc 16} Constitution saving throw. On a failed save, the target takes 22 ({@damage 4d10}) lightning damage, and the death kiss regains half as many hit points.

^Tags: #monster #type_aberration