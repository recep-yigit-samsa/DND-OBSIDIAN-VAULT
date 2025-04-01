# Glass Gator

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Glass Gator | Beast | 1 | 45 (7d10 + 7) | 15 | walk: 30 ft., swim: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Claw | 2d6 + 2 | - | - |
| Constrict | 1d6 + 2 + 2d4 | 12 | - |


**Claw.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d6 + 2}) slashing damage.

**Constrict.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature. {@h}5 ({@damage 1d6 + 2}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 12}). Until the grapple ends, the target is {@condition restrained} and takes 5 ({@damage 2d4}) poison damage at the start of each of its turns, and the glass gator can't use Constrict on another target.

^Tags: #monster #type_beast