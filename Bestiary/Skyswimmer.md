# Skyswimmer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Skyswimmer | Monstrosity | 13 | 216 (16d20 + 48) | 18 | walk: 10 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 6 + 6d6 | 19 | - |
| Slam | 2d12 + 6 | - | - |


**Multiattack.** The skyswimmer makes three attacks: one with its bite and two with its slam.

**Bite.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}22 ({@damage 3d10 + 6}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 19} Dexterity saving throw or be swallowed by the skyswimmer. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the skyswimmer, and it takes 21 ({@damage 6d6}) acid damage at the start of each of the skyswimmer's turns. If the skyswimmer takes 30 damage or more on a single turn from the swallowed creature, the skyswimmer must succeed on a {@dc 18} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 10 feet of the skyswimmer. If the skyswimmer dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 15 feet of movement, exiting {@condition prone}.

**Slam.** {@atk mw} {@hit 11} to hit, reach 30 ft., one target. {@h}19 ({@damage 2d12 + 6}) bludgeoning damage.

^Tags: #monster #type_monstrosity