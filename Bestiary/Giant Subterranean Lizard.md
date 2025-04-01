# Giant Subterranean Lizard

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Subterranean Lizard | Beast | 4 | 66 (7d12 + 21) | 14 | walk: 30 ft., swim: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 | 15 | - |
| Tail | 2d6 + 5 | 15 | - |
| Swallow | 2d10 + 5 + 3d6 | - | - |


**Multiattack.** The lizard makes two attacks: one with its bite and one with its tail. One attack can be replaced by Swallow.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage and the target is {@condition grappled} (escape {@dc 15}). Until this grapple ends, the target is {@condition restrained}, and the lizard can't bite another target.

**Tail.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage. If the target is a creature, it must succeed on a {@dc 15} Strength saving throw or be knocked {@condition prone}.

**Swallow.** {@atk mw} {@hit 7} to hit, reach 5 ft., one Medium or smaller creature the lizard is grappling. {@h}16 ({@damage 2d10 + 5}) piercing damage. The target is swallowed, and the grapple ends. The swallowed target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the lizard, and it takes 10 ({@damage 3d6}) acid damage at the start of each of the lizard's turns. The lizard can have only one target swallowed at a time. If the lizard dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 10 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_beast