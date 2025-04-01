# Beanstalk Wurm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Beanstalk Wurm | Monstrosity | 18 | 231 (14d20 + 84) | 16 | walk: 50 ft., climb: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 5d8 + 8 + 8d6 | 22 | - |


**Multiattack.** The wurm makes two Bite attacks.

**Bite.** {@atk mw} {@hit 14} to hit, reach 15 ft., one target. {@h}30 ({@damage 5d8 + 8}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 22} Dexterity saving throw or be swallowed by the wurm. A swallowed creature has the {@condition restrained} condition, has {@quickref Cover||3||total cover} against attacks and other effects outside the wurm, and takes 28 ({@damage 8d6}) piercing damage at the start of each of the wurm's turns from thorns in the wurm's gullet. The wurm's stomach can hold up to two creatures at a time. If the wurm takes 30 damage or more on a single turn from a creature inside it, the wurm must succeed on a {@dc 22} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the wurm and has the {@condition prone} condition. If the wurm dies, a swallowed creature no longer has the {@condition restrained} condition and can escape from the corpse by using 10 feet of movement, exiting with the {@condition prone} condition.

^Tags: #monster #type_monstrosity