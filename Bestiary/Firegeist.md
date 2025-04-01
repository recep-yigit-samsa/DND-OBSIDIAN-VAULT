# Firegeist

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Firegeist | Elemental | 2 | 82 (15d6 + 30) | 14 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Burning Slam | 1d6 + 4 + 2d6 + 1d6 | 13 | - |
| Burning Terror {@recharge 5} | 4d6 + 1d6 | 13 | - |


**Burning Slam.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d6 + 4}) bludgeoning damage plus 7 ({@damage 2d6}) fire damage. If the target is a flammable object, it ignites. If the target is a creature, the target must succeed on a {@dc 13} Dexterity saving throw or ignite. Until a creature takes an action to douse the fire, the target takes 3 ({@damage 1d6}) fire damage at the start of each of its turns.

**Burning Terror {@recharge 5}.** The firegeist assaults the mind of one creature it can see within 30 feet of it with the painful, humiliating memory of the firegeist's first death. The target must make a {@dc 13} Wisdom saving throw. On a failure, the target takes 14 ({@damage 4d6}) fire damage and is {@condition frightened} for 1 minute. On a success, the target takes half the damage and isn't {@condition frightened}. While {@condition frightened}, the creature takes 3 ({@damage 1d6}) fire damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_elemental