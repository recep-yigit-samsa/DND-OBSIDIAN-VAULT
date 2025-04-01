# Zimwi

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Zimwi | Giant | 5 | 119 (13d8 + 52) | 16 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 4 | - | - |
| Claws | 2d6 + 4 | 12 | - |
| Swallow | 3d6 | 14 | - |


**Multiattack.** The zimwi makes one Bite attack and one Claw attack. It can replace its Bite attack with a use of Swallow.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage.

**Claws.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage, and the target is {@condition grappled} (escape {@dc 12}) if it is a Medium or smaller creature. The zimwi has two claws, each of which can grapple only one target.

**Swallow.** The zimwi makes one Bite attack against a Medium or smaller creature it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the zimwi, and it takes 10 ({@damage 3d6}) acid damage at the start of each of the zimwi's turns. A zimwi can have up to two creatures swallowed at a time. If the zimwi takes 20 damage or more on a single turn from a swallowed creature, the zimwi must succeed on a {@dc 14} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 5 feet of the zimwi. If the zimwi dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 5 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_giant