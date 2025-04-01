# Hythonia

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hythonia | Monstrosity | 17 | 199 (21d10 + 84) | 17 | walk: 40 ft., climb: 40 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claws | 1d8 + 5 + 1d8 | - | - |
| Constrict | 2d10 + 5 + 3d6 + 5 | 19 | - |
| Snaky Hair | 4d12 + 5 | - | - |


**Multiattack.** Hythonia makes three attacks: one with her claws, one to constrict, and one with her snaky hair.

**Claws.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d8 + 5}) slashing damage plus 4 ({@damage 1d8}) poison damage.

**Constrict.** {@atk mw} {@hit 11} to hit, reach 15 ft., one Large or smaller creature. {@h}16 ({@damage 2d10 + 5}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 19}). Until this grapple ends, the target is {@condition restrained} and takes 15 ({@damage 3d6 + 5}) bludgeoning damage at the start of each of its turns, and Hythonia can't constrict another target.

**Snaky Hair.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}31 ({@damage 4d12 + 5}) bludgeoning damage, and Hythonia can pull the target up to 5 feet closer to her if it is a Large or smaller creature.

^Tags: #monster #type_monstrosity