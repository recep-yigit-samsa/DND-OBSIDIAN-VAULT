# Neogi

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Neogi | Aberration | 3 | 33 (6d6 + 12) | 15 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 3 + 4d6 | 12 | - |
| Claws | 2d4 + 3 | - | - |
| Enslave (Recharges after a Short or Long Rest) | - | 14 | - |


**Multiattack.** The neogi makes two attacks: one with its bite and one with its claws.

**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage plus 14 ({@damage 4d6}) poison damage, and the target must succeed on a {@dc 12} Constitution saving throw or become {@condition poisoned} for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Claws.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}8 ({@damage 2d4 + 3}) slashing damage.

**Enslave (Recharges after a Short or Long Rest).** The neogi targets one creature it can see within 30 feet of it. The target must succeed on a {@dc 14} Wisdom saving throw or be magically {@condition charmed} by the neogi for 1 day, or until the neogi dies or is more than 1 mile from the target. The {@condition charmed} target obeys the neogi's commands and can't take reactions, and the neogi and the target can communicate telepathically with each other at a distance of up to 1 mile. Whenever the {@condition charmed} target takes damage, it can repeat the saving throw, ending the effect on itself on a success.

^Tags: #monster #type_aberration