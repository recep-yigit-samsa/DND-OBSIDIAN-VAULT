# Purple Wormling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Purple Wormling | Monstrosity | 2 | 42 (5d10 + 15) | 12 | walk: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d8 + 5 + 1d6 | 13 | - |
| Tail Stinger | 1d4 + 3 + 3d6 | 13 | - |


**Multiattack.** The wormling makes two attacks: one with its bite and one with its stinger.

**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 5}) piercing damage. If the target is a Small or smaller creature, it must succeed on a {@dc 13} Dexterity saving throw or be swallowed by the worm. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the wormling, and it takes 3 ({@damage 1d6}) acid damage at the start of each of the wormling's turns. If the wormling takes 10 damage or more on a single turn from a creature inside it, the wormling must succeed on a {@dc 21} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the wormling. If the wormling dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 5 feet of movement, exiting {@condition prone}.

**Tail Stinger.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}5 ({@damage 1d4 + 3}) piercing damage, and the target must make a {@dc 13} Constitution saving throw, taking 10 ({@damage 3d6}) poison damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_monstrosity