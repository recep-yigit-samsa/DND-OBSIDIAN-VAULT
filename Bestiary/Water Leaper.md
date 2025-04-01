# Water Leaper

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Water Leaper | Monstrosity | 4 | 97 (13d10 + 26) | 14 | walk: 5 ft., fly: 50 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 3 | 13 | - |
| Stinger | 2d8 + 3 + 2d4 | 13 | - |
| Swallow | 2d6 | 12 | - |


**Multiattack.** The water leaper makes one Bite attack and one Stinger attack.

**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) piercing damage, and the target is {@condition grappled} (escape {@dc 13}). Until this grapple ends, the target is {@condition restrained}, and the water leaper can't Bite another target.

**Stinger.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d8 + 3}) piercing damage, and the target must succeed on a {@dc 13} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned} in this way, the creature takes 5 ({@damage 2d4}) poison damage at the start of each of its turns. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Swallow.** The water leaper makes a Bite attack against a Medium or smaller creature it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the water leaper, and it takes 7 ({@damage 2d6}) acid damage at the start of each of the water leaper's turns. The water leaper can have only one creature swallowed at a time. If the water leaper takes 15 damage or more on a single turn from the swallowed creature, the leaper must succeed on a {@dc 12} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 5 feet of the leaper. If the leaper dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 10 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_monstrosity