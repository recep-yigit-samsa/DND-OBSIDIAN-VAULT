# Flab Giant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Flab Giant | Giant | 4 | 110 (13d10 + 39) | 14 | walk: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 15 | - |
| Slam | 2d6 + 5 | - | - |
| Squatting Pin | 5d6 + 5 + 1d6 + 5 | 15 | - |


**Multiattack.** The giant makes two Slam attacks. If both attacks hit a Medium or smaller creature, the target is {@condition grappled} (escape {@dc 15}).

**Slam.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) bludgeoning damage.

**Squatting Pin.** One creature {@condition grappled} by the flab giant must make a {@dc 15} Strength saving throw. On a failure, a creature takes 22 ({@damage 5d6 + 5}) bludgeoning damage and is {@condition restrained} until the grapple ends. On a success, a creature takes half the damage and isn't {@condition restrained}, but it remains {@condition grappled} until it escapes. While {@condition restrained}, a creature takes 8 ({@damage 1d6 + 5}) bludgeoning damage at the start of each of the giant's turns. If the flab giant moves, the target is no longer {@condition restrained} or {@condition grappled}.

^Tags: #monster #type_giant