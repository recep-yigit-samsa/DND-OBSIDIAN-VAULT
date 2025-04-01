# Giant Toad

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Toad | Beast | 1 | 39 (6d10 + 6) | 11 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d6 + 2 + 2d4 | 12 | - |
| Swallow | 3d6 | - | - |


**Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}5 ({@damage 1d6 + 2}) Piercing damage plus 5 ({@damage 2d4}) Poison damage. If the target is a Medium or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 12}).

**Swallow.** The toad swallows a Medium or smaller target it is grappling. While swallowed, the target isn't {@condition Grappled|XPHB} but has the {@condition Blinded|XPHB} and {@condition Restrained|XPHB} conditions, and it has {@variantrule Cover|XPHB|Total Cover} against attacks and other effects outside the toad. In addition, the target takes 10 ({@damage 3d6}) Acid damage at the end of each of the toad's turns. The toad can have only one target swallowed at a time, and it can't use Bite while it has a swallowed target. If the toad dies, a swallowed creature is no longer {@condition Restrained|XPHB} and can escape from the corpse using 5 feet of movement, exiting with the {@condition Prone|XPHB} condition.

^Tags: #monster #type_beast