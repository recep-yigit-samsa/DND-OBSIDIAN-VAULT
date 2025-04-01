# Otyugh Mutate

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Otyugh Mutate | Aberration | 6 | 76 (8d10 + 32) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 4 | 15 | - |
| Tentacle | 2d8 + 4 | 15 | - |
| Chitin Slam | 3d10 | 15 | - |


**Multiattack.** The mutate makes two Bite or Tentacle attacks. It can replace one of these attacks with Chitin Slam.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage. If the target is a creature, it must succeed on a {@dc 15} Constitution saving throw or have the {@condition poisoned} condition. Every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by 5 ({@dice 1d10}) on a failure. On a successful save, the target is no longer {@condition poisoned}. The target dies if its hit point maximum is reduced to 0. This reduction to the target's hit point maximum lasts until it no longer has the {@condition poisoned} condition.

**Tentacle.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}13 ({@damage 2d8 + 4}) bludgeoning damage, and if the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 15}) and the {@condition restrained} condition until this grapple ends. The mutate has two tentacles that can grapple one target each.

**Chitin Slam.** The mutate targets one creature it is grappling, slamming the creature against its chitinous plating. The creature must succeed on a {@dc 15} Constitution saving throw or take 16 ({@damage 3d10}) bludgeoning damage and have the {@condition stunned} condition until the end of the mutate's next turn.

^Tags: #monster #type_aberration