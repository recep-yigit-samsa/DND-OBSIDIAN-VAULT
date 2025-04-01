# Brown Scavver

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Brown Scavver | Monstrosity | 4 | 51 (6d10 + 18) | 13 | walk: 0 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Swallowing Bite | 2d6 + 4 + 3d8 | 13 | - |


**Swallowing Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage. If the target is a Medium or smaller creature, it must succeed on a {@dc 13} Dexterity saving throw or be swallowed by the scavver. The scavver can have one creature swallowed at a time. A swallowed creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects outside the scavver, and takes 13 ({@damage 3d8}) poison damage at the start of each of the scavver's turns from the poisonous gas in the scavver's gullet. If the scavver takes 15 damage or more on a single turn from a creature inside it, the scavver must succeed on a {@dc 20} Constitution saving throw at the end of that turn or regurgitate the swallowed creature, which falls {@condition prone} in a space within 10 feet of the scavver. If the scavver dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 10 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_monstrosity