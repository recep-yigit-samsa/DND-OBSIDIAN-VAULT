# Mind Flayer Psion

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mind Flayer Psion | Aberration | 8 | 71 (13d8 + 13) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tentacles | 2d10 + 4 | 15 | - |
| Extract Brain | 10d10 | - | - |
| Mind Blast {@recharge 5} | 4d8 + 4 | 15 | - |


**Tentacles.** {@atk mw} {@hit 7} to hit, reach 5 ft., one creature. {@h}15 ({@damage 2d10 + 4}) psychic damage. If the target is Medium or smaller, it is {@condition grappled} (escape {@dc 15}) and must succeed on a {@dc 15} Intelligence saving throw or be {@condition stunned} until this grapple ends.

**Extract Brain.** {@atk mw} {@hit 7} to hit, reach 5 ft., one {@condition incapacitated} humanoid {@condition grappled} by the mind flayer. {@h}The target takes 55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills the target by extracting and devouring its brain.

**Mind Blast {@recharge 5}.** The mind flayer magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a {@dc 15} Intelligence saving throw or take 22 ({@damage 4d8 + 4}) psychic damage and be {@condition stunned} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration