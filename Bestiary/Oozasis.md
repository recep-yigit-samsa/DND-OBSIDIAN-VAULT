# Oozasis

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Oozasis | Ooze | 9 | 217 (14d20 + 70) | 7 | walk: 20 ft., burrow: 20 ft., swim: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pseudopod | 2d8 + 4 + 2d6 | 16 | - |
| Compelling Vapors {@recharge 5} | 10d8 | 16 | - |


**Multiattack.** The oozasis makes three Pseudopod attacks.

**Pseudopod.** {@atk mw} {@hit 8} to hit, reach 15 ft., one target. {@h}13 ({@damage 2d8 + 4}) bludgeoning damage plus 7 ({@damage 2d6}) acid damage. If the target is a Large or smaller creature, it is {@condition grappled} (escape {@dc 16}). Until this grapple ends, the target is {@condition restrained}. The oozasis can have up to two creatures {@condition grappled} at a time.

**Compelling Vapors {@recharge 5}.** The oozasis emits mind-altering vapors. Each creature within 20 feet of the oozasis must make a {@dc 16} Constitution saving throw. On a failure, a creature takes 45 ({@damage 10d8}) psychic damage and suffers either tranquility or turmoil for minute. On a success, a creature takes half the damage and doesn't suffer tranquility or turmoil. A creature suffering tranquility is {@condition charmed} and can't attack. A creature suffering turmoil is unable to distinguish friend from foe and must move to and attack the nearest creature other than the oozasis on each of its turns, stalking off in a random direction if no creature is in range. A creature suffering tranquility or turmoil can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_ooze