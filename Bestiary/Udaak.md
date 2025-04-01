# Udaak

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Udaak | Fiend | 16 | 165 (10d20 + 60) | 18 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 8 | 21 | - |
| Slam | 3d8 + 8 | - | - |
| Swallow | 6d6 | 21 | - |


**Multiattack.** The udaak makes three attacks: one with its bite and two with its slam.

**Bite.** {@atk mw} {@hit 13} to hit, reach 5 ft., one creature. {@h}21 ({@damage 2d12 + 8}) piercing damage, and the target is {@condition grappled} (escape {@dc 21}). Until this grapple ends, the target is {@condition restrained}, and the udaak can't bite another target.

**Slam.** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}21 ({@damage 3d8 + 8}) bludgeoning damage.

**Swallow.** The udaak makes one bite attack against a Large or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the udaak, and it takes 21 ({@damage 6d6}) acid damage at the start of each of the udaak's turns. If the udaak takes 30 damage or more on a single turn from a creature inside it, the udaak must succeed on a {@dc 21} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the udaak. If the udaak dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_fiend