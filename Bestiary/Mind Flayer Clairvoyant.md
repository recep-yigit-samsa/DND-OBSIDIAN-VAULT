# Mind Flayer Clairvoyant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mind Flayer Clairvoyant | Aberration | 11 | 156 (24d8 + 48) | 15 | walk: 30 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 3d10 + 5 | 17 | - |
| Extract Brain | 10d10 | - | - |
| Unleash Void {@recharge 5} | 4d8 + 4d8 | 17 | - |


**Multiattack.** The mind flayer makes two Tentacle attacks.

**Tentacle.** {@atk mw} {@hit 9} to hit, reach 5 ft., one creature. {@h}21 ({@damage 3d10 + 5}) psychic damage. If the target is Medium or smaller, it has the {@condition grappled} condition (escape {@dc 17}) and must succeed on a {@dc 17} Intelligence saving throw or have the {@condition incapacitated} condition until the grapple ends.

**Extract Brain.** {@atk mw} {@hit 9} to hit, reach 5 ft., one {@condition incapacitated} Humanoid {@condition grappled} by the mind flayer. {@h}55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills it by extracting and devouring its brain.

**Unleash Void {@recharge 5}.** The mind flayer opens a rift into the Far Realm, centered on a point the mind flayer can see within 60 feet of itself, and a tentacle lashes across creatures near the rift. Each creature other than mind flayers within 30 feet of the rift must make a {@dc 17} Intelligence saving throw, after which the tentacle disappears and the rift closes. On a failed save, a creature takes 18 ({@damage 4d8}) cold damage from the rift plus 18 ({@damage 4d8}) psychic damage from the tentacle and has the {@condition stunned} condition for 1 minute. On a successful save, a creature takes half as much damage only. A {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration