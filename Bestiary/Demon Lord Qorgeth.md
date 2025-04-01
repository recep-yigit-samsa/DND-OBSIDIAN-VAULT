# Demon Lord Qorgeth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Demon Lord Qorgeth | Unknown | 23 | 370 (20d20 + 160) | 21 | walk: 50 ft., burrow: 50 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 9 + 3d10 | 21 | - |
| Crush | 2d10 + 9 | 21 | - |
| Stinger | 4d6 + 9 + 6d10 | 21 | - |


**Multiattack.** Qorgeth makes one Bite attack, two Crush attacks, and one Stinger attack.

**Bite.** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. {@h}22 ({@damage 2d12 + 9}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 21} Dexterity saving throw or be swallowed by Qorgeth. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the worm, and it takes 16 ({@damage 3d10}) necrotic damage at the start of each of Qorgeth's turns. If Qorgeth takes 50 damage or more in a single turn from a creature inside it, Qorgeth must succeed on a {@dc 25} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of Qorgeth. If Qorgeth dies, a swallowed creature is no longer {@condition restrained} by it and can escape the corpse by spending 30 feet of movement, exiting {@condition prone}.

**Crush.** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. {@h}20 ({@damage 2d10 + 9}) bludgeoning damage, and if the target is a Large or smaller creature, it is {@condition restrained} until Qorgeth moves. A creature, including the {@condition restrained} creature, can use an action to free the {@condition restrained} creature by succeeding on a {@dc 21} Strength check.

**Stinger.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}23 ({@damage 4d6 + 9}) piercing damage, and the target must make a {@dc 21} Constitution saving throw. On a failure, the target takes 33 ({@damage 6d10}) poison damage and is {@condition poisoned} for 1 hour. On a success, the target takes half the damage and isn't {@condition poisoned}. A creature that fails the saving throw by 10 or more is also {@condition paralyzed} while {@condition poisoned} in this way.

^Tags: #monster #type_unknown