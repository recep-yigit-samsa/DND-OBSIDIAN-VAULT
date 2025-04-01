# Putrid Haunt

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Putrid Haunt | Undead | 2 | 44 (8d8 + 8) | 13 | walk: 30 ft., swim: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Slam | 2d8 + 3 + 2d4 | - | - |
| Expel Vermin {@recharge} | 2d6 + 2d6 | 13 | - |


**Slam.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d8 + 3}) bludgeoning damage plus 5 ({@damage 2d4}) poison damage.

**Expel Vermin {@recharge}.** The putrid haunt vomits forth the leeches, stinging insects, and other swamp vermin infesting its innards in a 15-foot cone. Each creature in the area must make a {@dc 13} Dexterity saving throw. On a failure, a creature takes 7 ({@damage 2d6}) piercing damage and 7 ({@damage 2d6}) poison damage and is {@condition poisoned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition poisoned}. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_undead