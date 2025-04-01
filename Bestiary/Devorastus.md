# Devorastus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Devorastus | Unknown | 20 | 275 (22d12 + 132) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pseudopod | 12d6 | - | - |
| Spit | 8d6 | 21 | - |
| Engulf | 10d6 + 12d6 | 21 | - |


**Multiattack.** Devorastus makes four attacks using its Pseudopod, Spit, or a combination of the two.

**Pseudopod.** {@atk mw} {@hit 13} to hit, reach 20 ft., one target. {@h}42 ({@damage 12d6}) acid damage.

**Spit.** {@atk rw} {@hit 8} to hit, range 100/200 ft., one target. {@h}28 ({@damage 8d6}) acid damage. A target hit by this attack must make a {@dc 21} Constitution saving throw. On a failed save, the target has the {@condition prone} condition.

**Engulf.** Devorastus moves up to its speed. While doing so, it can enter Large or smaller creatures' spaces. Whenever Devorastus enters a creature's space, the creature must make a {@dc 21} Dexterity saving throw. On a successful save, the creature can choose to be pushed 5 feet back or to the side of Devorastus. A creature that chooses not to be pushed suffers the consequences of a failed saving throw. On a failed save, Devorastus enters the creature's space, the creature takes 35 ({@damage 10d6}) acid damage, and is engulfed. The engulfed creature can't breathe, has the {@condition restrained} condition, and takes 42 ({@damage 12d6}) acid damage at the start of each of Devorastus' turns. When Devorastus moves, the engulfed creature moves with it. An engulfed creature can try to escape by making a {@dc 21} Strength check as an action. On a success, the creature escapes and enters a space of its choice within 5 feet of Devorastus.

^Tags: #monster #type_unknown