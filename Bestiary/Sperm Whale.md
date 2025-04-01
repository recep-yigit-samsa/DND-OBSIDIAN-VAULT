# Sperm Whale

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sperm Whale | Beast | 8 | 189 (14d20 + 42) | 13 | walk: 0 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 8 + 1d6 | 14 | - |
| Tail | 3d6 + 8 + 6d6 + 16 | - | - |


**Multiattack.** The whale makes two attacks: one with its bite and one with its tail.

**Bite.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}21 ({@damage 3d8 + 8}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 14} Dexterity saving throw or be swallowed by the whale. A swallowed creature has {@quickref Cover||3||total cover} against attacks and other effects outside the whale, and it takes 3 ({@damage 1d6}) acid damage at the start of each of the whale's turns. If the whale takes 30 damage or more on a single turn from a creature inside it, the whale must succeed on a {@dc 16} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the whale. If the whale dies, a swallowed creature can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

**Tail.** {@atk mw} {@hit 11} to hit, reach 15 ft., one target. {@h}18 ({@damage 3d6 + 8}) bludgeoning damage, or 37 ({@damage 6d6 + 16}) bludgeoning damage if the target is an object.

^Tags: #monster #type_beast