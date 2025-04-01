# Void Scavver

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Void Scavver | Monstrosity | 11 | 157 (15d12 + 60) | 15 | walk: 0 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Swallowing Bite | 6d12 + 6 + 2d10 | 16 | - |


**Swallowing Bite.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}45 ({@damage 6d12 + 6}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 16} Dexterity saving throw or be swallowed by the scavver. The scavver can have one creature swallowed at a time. A swallowed creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects outside the scavver, and takes 11 ({@damage 2d10}) acid damage at the start of each of the scavver's turns from the digestive juices in the scavver's gullet. If the scavver takes 25 damage or more on a single turn from a creature inside it, the scavver must succeed on a {@dc 20} Constitution saving throw at the end of that turn or regurgitate the swallowed creature, which falls {@condition prone} in a space within 10 feet of the scavver. If the scavver dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 10 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_monstrosity