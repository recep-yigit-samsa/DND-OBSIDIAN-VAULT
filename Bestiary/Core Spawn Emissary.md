# Core Spawn Emissary

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Core Spawn Emissary | Aberration | 6 | 102 (12d8 + 48) | 15 | walk: 40 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Talons | 2d10 + 3 | - | - |
| Alluring Thrum {@recharge 5} | - | 14 | - |
| Crystal Spores {@recharge} | 2d10 | 14 | - |


**Multiattack.** The emissary makes three talons attacks.

**Talons.** {@atk mw} {@hit 6} to hit, reach 5 ft., one creature. {@h}14 ({@damage 2d10 + 3}) slashing damage.

**Alluring Thrum {@recharge 5}.** The emissary emits a dreadful yet alluring hum. Each creature within 20 feet of the emissary that can hear it and that isn't an aberration must succeed on a {@dc 14} Constitution saving throw or be {@condition charmed} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Crystal Spores {@recharge}.** A 15-foot-radius cloud of toxic crystalline spores extends out from the emissary. The spores spread around corners. Each creature in the area must succeed on a {@dc 14} Constitution saving throw or become {@condition poisoned}. While {@condition poisoned} in this way, a creature takes 11 ({@damage 2d10}) poison damage at the start of each of its turns. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration