# Giant Frog

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Frog | Beast | 1/4 | 18 (4d8) | 11 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d6 + 2 | 11 | - |
| Swallow | 2d4 | - | - |


**Bite.** {@atkr m} {@hit 3}, reach 5 ft. {@h}5 ({@damage 1d6 + 2}) Piercing damage. If the target is a Medium or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 11}).

**Swallow.** The frog swallows a Small or smaller target it is grappling. While swallowed, the target isn't {@condition Grappled|XPHB} but has the {@condition Blinded|XPHB} and {@condition Restrained|XPHB} conditions, and it has {@variantrule Cover|XPHB|Total Cover} against attacks and other effects outside the frog. While swallowing the target, the frog can't use Bite, and if the frog dies, the swallowed target is no longer {@condition Restrained|XPHB} and can escape from the corpse using 5 feet of movement, exiting with the {@condition Prone|XPHB} condition. At the end of the frog's next turn, the swallowed target takes 5 ({@damage 2d4}) Acid damage. If that damage doesn't kill it, the frog disgorges it, causing it to exit {@condition Prone|XPHB}.

^Tags: #monster #type_beast