# Styx Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Styx Dragon | Dragon | 20 | 296 (16d20 + 128) | 17 | walk: 30 ft., burrow: 20 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 8 + 2d6 | 19 | - |
| Tail | 2d6 + 8 | 22 | - |
| Constrict | 3d12 + 8 | 19 | - |
| Frightful Presence | - | 18 | - |
| Stygian Breath {@recharge 5} | 12d8 | 19 | - |


**Multiattack.** The dragon can use its Frightful Presence. It then makes three attacks using its Bite, Tail, or a combination of the two. It can replace one of the attacks with Constrict.

**Bite.** {@atk mw} {@hit 14} to hit, reach 5 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage plus 7 ({@damage 2d6}) poison damage, and the target must make a {@dc 19} Constitution saving throw. On a failed save, the target contracts Stygian Wasting.

**Tail.** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d6 + 8}) bludgeoning damage. If the target is a Large or smaller creature, it has the {@condition grappled} condition (escape {@dc 22}). The dragon can't make a Tail attack while a creature is {@condition grappled} in this way.

**Constrict.** The dragon tightens its grip on a creature {@condition grappled} by its tail. The creature takes 27 ({@damage 3d12 + 8}) bludgeoning damage, has the {@condition restrained} condition until the start of the dragon's next turn, and must make a {@dc 19} Constitution saving throw. On a failed save, the target contracts Stygian Wasting.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon must succeed on a {@dc 18} Wisdom saving throw or have the {@condition frightened} condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Stygian Breath {@recharge 5}.** The dragon exhales poisonous Styx water in a 60-foot-long, 10-foot-wide line. Each creature in that line must make a {@dc 19} Dexterity saving throw, taking 54 ({@damage 12d8}) poison damage on a failed save, or half as much on a successful one. Creatures that fail the save contract Stygian Wasting.

^Tags: #monster #type_dragon