# Giant Ice Toad

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Ice Toad | Monstrosity | 3 | 52 (7d10 + 14) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d6 + 3 | 13 | - |
| Swallow | 2d6 + 3 + 3d6 + 2d10 | - | - |


**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) piercing damage, and the target is {@condition grappled} (escape {@dc 13}). Until this grapple ends, the target is {@condition restrained}, and the toad can't bite another target.

**Swallow.** {@atk mw} {@hit 5} to hit, reach 5 ft., one Medium or smaller creature the toad is grappling. {@h}10 ({@damage 2d6 + 3}) piercing damage, the target is swallowed, and the grapple ends. The swallowed target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the toad, and it takes 10 ({@damage 3d6}) acid damage and 11 ({@damage 2d10}) cold damage at the start of each of the toad's turns. The toad can have only one target swallowed at a time. If the toad dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 5 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_monstrosity