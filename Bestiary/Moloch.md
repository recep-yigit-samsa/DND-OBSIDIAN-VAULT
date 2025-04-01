# Moloch

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Moloch | Unknown | 21 | 253 (22d10 + 132) | 19 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d8 + 8 | - | - |
| Claw | 2d8 + 8 | - | - |
| Many-Tailed Whip | 2d4 + 8 + 2d10 | 24 | - |
| Breath of Despair {@recharge 5} | 5d10 | 21 | - |
| Teleport | - | - | - |


**Multiattack.** Moloch makes three attacks: one with his bite, one with his claw, and one with his whip.

**Bite.** {@atk mw} {@hit 15} to hit, reach 5 ft., one target. {@h}26 ({@damage 4d8 + 8}) piercing damage.

**Claw.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d8 + 8}) slashing damage.

**Many-Tailed Whip.** {@atk mw} {@hit 15} to hit, reach 30 ft., one target. {@h}13 ({@damage 2d4 + 8}) slashing damage plus 11 ({@damage 2d10}) lightning damage. If the target is a creature, it must succeed on a {@dc 24} Strength saving throw or be pulled up to 30 feet in a straight line toward Moloch.

**Breath of Despair {@recharge 5}.** Moloch exhales in a 30-foot cube. Each creature in that area must succeed on a {@dc 21} Wisdom saving throw or take 27 ({@damage 5d10}) psychic damage, drop whatever it is holding, and become {@condition frightened} for 1 minute. While {@condition frightened} in this way, a creature must take the Dash action and move away from Moloch by the safest available route on each of its turns, unless there is nowhere to move, in which case it needn't take the Dash action. If the creature ends its turn in a location where it doesn't have line of sight to Moloch, the creature can repeat the saving throw. On a success, the effect ends.

**Teleport.** Moloch magically teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.

^Tags: #monster #type_unknown