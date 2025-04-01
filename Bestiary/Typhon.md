# Typhon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Typhon | Monstrosity | 15 | 195 (17d12 + 85) | 17 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Flurry of Bites | 8d6 + 7 | - | - |
| Constrict | 3d6 + 7 + 3d6 + 7 | 19 | - |
| Maw | 3d12 + 7 + 3d12 | - | - |


**Multiattack.** The typhon makes three attacks: one with its Flurry of Bites, one to constrict, and one with its maw.

**Flurry of Bites.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}35 ({@damage 8d6 + 7}) piercing damage.

**Constrict.** {@atk mw} {@hit 12} to hit, reach 15 ft., one Large or smaller creature. {@h}17 ({@damage 3d6 + 7}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 19}). Until this grapple ends, the target is {@condition restrained} and takes 17 ({@damage 3d6 + 7}) bludgeoning damage at the start of each of its turns. The typhon can have up to two creatures constricted.

**Maw.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}26 ({@damage 3d12 + 7}) piercing damage plus 19 ({@damage 3d12}) acid damage.

^Tags: #monster #type_monstrosity