# Titanoboa

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Titanoboa | Beast | 12 | 232 (15d20 + 75) | 14 | walk: 40 ft., climb: 40 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 5d8 + 8 | - | - |
| Constrict | 4d10 + 8 | 18 | - |
| Swallow | 6d6 | 15 | - |


**Multiattack.** The titanoboa makes two Bite attacks or one Bite attack and one Constrict attack. It can replace one Bite attack with a use of Swallow.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}30 ({@damage 5d8 + 8}) piercing damage.

**Constrict.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}30 ({@damage 4d10 + 8}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 18}) if it is a Huge or smaller creature. Until this grapple ends, the target is {@condition restrained}, and the titanoboa can't Constrict another target.

**Swallow.** The titanoboa makes one Bite attack against a Huge or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the titanoboa, and it takes 21 ({@damage 6d6}) acid damage at the start of each of the titanoboa's turns. If the titanoboa takes 30 damage or more on a single turn from a swallowed creature, the titanoboa must succeed on a {@dc 15} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the titanoboa. If the titanoboa dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_beast