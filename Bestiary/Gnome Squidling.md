# Gnome Squidling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gnome Squidling | Aberration | 1/2 | 10 (3d6) | 8 | walk: 15 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tentacles | 2d4 | 7 | - |
| Extract Brain | 5d10 | - | - |
| Mind Tickle {@recharge 5} | 1d4 | 7 | - |


**Tentacles.** {@atk mw} {@hit 0} to hit, reach 5 ft., one creature. {@h}5 ({@damage 2d4}) psychic damage. If the target is Medium or smaller, it is {@condition grappled} (escape {@dc 7}) and must succeed on a {@dc 7} Intelligence saving throw or be {@condition stunned} until this grapple ends.

**Extract Brain.** {@atk mw} {@hit 0} to hit, reach 5 ft., one {@condition incapacitated} creature {@condition grappled} by the squidling. {@h}27 ({@damage 5d10}) piercing damage. If this damage reduces the target to 0 hit points, the squidling kills the target by extracting and devouring its brain.

**Mind Tickle {@recharge 5}.** The squidling magically emits psychic energy in a 30-foot cone. Each creature in that area must succeed on a {@dc 7} Intelligence saving throw or take 2 ({@damage 1d4}) psychic damage and be {@condition stunned} until the end of its next turn.

^Tags: #monster #type_aberration