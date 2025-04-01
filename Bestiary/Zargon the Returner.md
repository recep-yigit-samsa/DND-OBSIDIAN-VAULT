# Zargon the Returner

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Zargon the Returner | Aberration | 17 | 253 (22d12 + 110) | 18 | walk: 40 ft., swim: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Barbed Tentacle | 2d8 + 6 | 20 | - |
| Bite | 2d12 + 6 + 2d6 | - | - |
| Gore | 2d8 + 6 | - | - |
| Slime Wave {@recharge 5} | 7d10 | 19 | - |


**Multiattack.** Zargon makes two Barbed Tentacle attacks, one Bite attack, and one Gore attack.

**Barbed Tentacle.** {@atk mw} {@hit 12} to hit, reach 20 ft., one target. {@h}15 ({@damage 2d8 + 6}) piercing damage. If the target is a Large or smaller creature, it has the {@condition grappled} condition (escape {@dc 20}), and Zargon can pull the creature up to 20 feet straight toward itself. Zargon has six tentacles, each of which can grapple one creature. Zargon can move at its full speed while dragging creatures it is grappling.

**Bite.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}19 ({@damage 2d12 + 6}) piercing damage plus 7 ({@damage 2d6}) acid damage.

**Gore.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d8 + 6}) force damage, and a 10-foot-radius {@condition invisible} sphere of antimagic, like that created by an {@spell Antimagic Field} spell, surrounds the target. The sphere is centered on the target, moves with the target, and lasts until the end of Zargon's next turn.

**Slime Wave {@recharge 5}.** Zargon spews slime in a 60-foot cone. Each creature in that area that isn't an Aberration or Ooze must make a {@dc 19} Constitution saving throw. On a failed save, the creature takes 38 ({@damage 7d10}) acid damage and has the {@condition poisoned} condition for 1 minute. On a successful save, the creature takes half as much damage only. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature reduced to 0 hit points by the acid damage dies and dissolves into a puddle of slime that rises as a gibbering mouther at the start of Zargon's next turn. The creature obeys Zargon's commands and takes its turn immediately after Zargon's. Only a {@spell Wish} spell can reverse this transformation and restore the creature to life.

^Tags: #monster #type_aberration