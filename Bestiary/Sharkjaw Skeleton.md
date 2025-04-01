# Sharkjaw Skeleton

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sharkjaw Skeleton | Undead | 1 | 45 (6d10 + 12) | 13 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d6 + 3 | 13 | - |
| Devouring Embrace | 2d6 | 13 | - |


**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) piercing damage. If the target is a Large or smaller creature, it is {@condition grappled} (escape {@dc 13}). The skeleton can grapple up to two targets at a time.

**Devouring Embrace.** The sharkjaw skeleton devours a Medium or smaller creature {@condition grappled} by it. The grapple ends, the devoured target is {@condition restrained} in the skeleton's many jaws, and the target takes 7 ({@damage 2d6}) piercing damage at the start of each of the skeleton's turns. If the skeleton moves, the devoured target moves with it. The skeleton can devour only one target at a time. A creature, including the devoured target, can take its action to pry the devoured target out of the skeleton's many jaws by succeeding on a {@dc 13} Strength check.

^Tags: #monster #type_undead