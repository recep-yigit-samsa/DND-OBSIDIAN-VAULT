# Core Spawn Worm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Core Spawn Worm | Aberration | 15 | 279 (18d20 + 90) | 18 | walk: 60 ft., burrow: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Barbed Tentacles | 5d6 + 8 | 18 | - |
| Bite | 5d8 + 8 + 6d6 | 18 | - |


**Multiattack.** The worm makes two attacks: one with its barbed tentacles and one with its bite.

**Barbed Tentacles.** {@atk mw} {@hit 13} to hit, reach 10 ft., one creature. {@h}25 ({@damage 5d6 + 8}) piercing damage, and the target is {@condition grappled} (escape {@dc 18}). Until this grapple ends, the target is {@condition restrained}. The tentacles can grapple only one creature at a time.

**Bite.** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}30 ({@damage 5d8 + 8}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 18} Dexterity saving throw or be swallowed by the worm. A swallowed creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects outside the worm, and takes 21 ({@damage 6d6}) fire damage at the start of each of the worm's turns. If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a {@dc 21} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the worm. If the worm dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_aberration