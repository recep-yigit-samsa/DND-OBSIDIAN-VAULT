# Frostveil

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Frostveil | Plant | 4 | 67 (9d8 + 27) | 16 | walk: 10 ft., fly: {'number': 15, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 15 | - |
| Frozen Tendril | 1d8 + 5 + 1d6 | - | - |
| Snowy Engulf | 1d8 + 1d6 | 15 | - |
| Spirit Spores {@recharge} | 6d6 | 15 | - |


**Multiattack.** The frostveil makes two Frozen Tendril attacks. If both attacks hit a Medium or smaller target, the target is {@condition grappled} (escape {@dc 15}), and the frostveil uses Snowy Engulf on it.

**Frozen Tendril.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}9 ({@damage 1d8 + 5}) bludgeoning damage plus 3 ({@damage 1d6}) cold damage.

**Snowy Engulf.** The frostveil engulfs a Medium or smaller creature {@condition grappled} by it. The engulfed target is {@condition blinded} and {@condition restrained}, and it must succeed on a {@dc 15} Constitution saving throw at the start of each of the frostveil's turns or take 4 ({@damage 1d8}) acid damage and 3 ({@damage 1d6}) cold damage. If the frostveil moves, the engulfed target moves with it. The frostveil can have only one creature engulfed at a time.

**Spirit Spores {@recharge}.** The frostveil releases a puff of psychotropic spores around itself. Each creature within 10 feet of the frostveil must make a {@dc 15} Constitution saving throw. On a failure, a creature takes 21 ({@damage 6d6}) cold damage and is {@condition incapacitated} for 1 minute. On a success, a creature takes half the damage and isn't {@condition incapacitated}. When an {@condition incapacitated} creature moves, it moves in a random direction. An {@condition incapacitated} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_plant