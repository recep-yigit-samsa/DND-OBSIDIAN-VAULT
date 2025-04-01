# Wurm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Wurm | Monstrosity | 14 | 200 (16d12 + 96) | 18 | walk: 50 ft., burrow: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 5d6 + 7 + 5d6 | 20 | - |


**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}24 ({@damage 5d6 + 7}) piercing damage. If the target is a Medium or smaller creature, it must succeed on a {@dc 20} Dexterity saving throw or be swallowed by the wurm. A swallowed creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects outside the wurm, and takes 17 ({@damage 5d6}) acid damage at the start of each of the wurm's turns. If the wurm takes 30 damage or more on a single turn from a creature inside it, the wurm must succeed on a {@dc 21} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the wurm. If the wurm dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_monstrosity