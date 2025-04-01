# Neothelid

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Neothelid | Aberration | 13 | 325 (21d20 + 105) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tentacles | 3d8 + 8 + 3d8 + 10d6 | 18 | - |
| Acid Breath {@recharge 5} | 10d6 | 18 | - |


**Tentacles.** {@atk mw} {@hit 13} to hit, reach 15 ft., one target. {@h}21 ({@damage 3d8 + 8}) bludgeoning damage plus 13 ({@damage 3d8}) psychic damage. If the target is a Large or smaller creature, it must succeed on a {@dc 18} Strength saving throw or be swallowed by the neothelid. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the neothelid, and it takes 35 ({@damage 10d6}) acid damage at the start of each of the neothelid's turns. If the neothelid takes 30 damage or more on a single turn from a creature inside it, the neothelid must succeed on a {@dc 18} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the neothelid. If the neothelid dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

**Acid Breath {@recharge 5}.** The neothelid exhales acid in a 60-foot cone. Each creature in that area must make a {@dc 18} Dexterity saving throw, taking 35 ({@damage 10d6}) acid damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_aberration