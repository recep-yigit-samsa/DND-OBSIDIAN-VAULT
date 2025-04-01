# Eye Monger

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Eye Monger | Aberration | 10 | 149 (13d10 + 78) | 17 | walk: 0 ft., fly: {'number': 20, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d6 + 5 + 10d6 | 18 | - |


**Bite.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage, and if the target is a Medium or smaller creature, it must succeed on a {@dc 18} Dexterity saving throw or be swallowed by the eye monger and deposited in the eye monger's gullet (see Antimagic Gullet). The eye monger can swallow one creature at a time. A swallowed creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects originating outside the eye monger, and takes 35 ({@damage 10d6}) acid damage at the start of each of its turns. If the eye monger takes 25 damage or more on a single turn from a creature inside its gullet, the eye monger regurgitates the swallowed creature, which falls {@condition prone} in a space within 10 feet of the eye monger. If the eye monger dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 10 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_aberration