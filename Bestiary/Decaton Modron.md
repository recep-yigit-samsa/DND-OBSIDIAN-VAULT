# Decaton Modron

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Decaton Modron | Construct | 8 | 144 (17d10 + 51) | 16 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 2d10 + 4 | 14 | - |
| Lightning Rays {@recharge} | 7d10 | 13 | - |


**Multiattack.** The decaton makes three Tentacle attacks.

**Tentacle.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage, and if the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 14}). Until this grapple ends, the decaton can't use this tentacle against other targets. The decaton has ten tentacles, each of which can grapple one target.

**Lightning Rays {@recharge}.** The decaton unleashes a barrage of lightning bolts from its eyes. Each creature within 30 feet of the decaton must make a {@dc 13} Dexterity saving throw, taking 38 ({@damage 7d10}) lightning damage on a failed save, or half as much damage on a successful save.

^Tags: #monster #type_construct