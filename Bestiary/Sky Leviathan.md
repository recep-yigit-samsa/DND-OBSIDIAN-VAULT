# Sky Leviathan

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sky Leviathan | Beast | 10 | 247 (15d20 + 90) | 14 | fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 3d8 + 9 + 6d6 | 18 | - |


**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}22 ({@damage 3d8 + 9}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 18} Dexterity saving throw or be swallowed by the leviathan. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the leviathan, and it takes 21 ({@damage 6d6}) acid damage at the start of each of the leviathan's turns. If the leviathan takes 30 damage or more on a single turn from a creature inside it, the leviathan must succeed on a {@dc 21} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the leviathan. If the leviathan dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_beast