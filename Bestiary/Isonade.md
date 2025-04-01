# Isonade

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Isonade | Monstrosity | 14 | 222 (12d20 + 96) | 18 | walk: 10 ft., swim: 100 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d12 + 10 + 6d6 | 18 | - |
| Tail Slap | 4d6 + 10 | - | - |
| Breach | 14d6 | 18 | - |


**Multiattack.** The isonade makes one Bite attack and two Tail Slap attacks.

**Bite.** {@atk mw} {@hit 15} to hit, reach 15 ft., one target. {@h}36 ({@damage 4d12 + 10}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 18} Dexterity saving throw or be swallowed by the isonade. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the isonade, and it takes 21 ({@damage 6d6}) acid damage at the start of each of the isonade's turns. An isonade can have no more than four creatures swallowed at a time. If the isonade takes 30 damage or more on a single turn from a creature inside it, it must succeed on a {@dc 23} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the isonade. If the isonade dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

**Tail Slap.** {@atk mw} {@hit 15} to hit, reach 15 ft., one target. {@h}24 ({@damage 4d6 + 10}) bludgeoning damage.

**Breach.** If the isonade swims at least 20 feet as part of its movement, it can use this action to emerge in a space on the surface of the water that contains one or more other creatures. Each of those creatures and each creature within 10 of the isonade's space must make a {@dc 18} Dexterity saving throw. On a failure, a creature takes 49 ({@damage 14d6}) bludgeoning damage and is knocked {@condition prone}. On a success, a creature takes half the damage and is pushed up to 10 feet out of the isonade's space into an unoccupied space of the creature's choice. If no unoccupied space is within range, the creature instead falls {@condition prone} in the isonade's space.

^Tags: #monster #type_monstrosity