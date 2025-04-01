# Ulitharid

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ulitharid | Aberration | 9 | 127 (17d10 + 14) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tentacles | 4d10 + 5 | 14 | - |
| Extract Brain | 10d10 | - | - |
| Mind Blast {@recharge 5} | 4d12 + 5 | 17 | - |


**Tentacles.** {@atk mw} {@hit 9} to hit, reach 10 ft., one creature. {@h}27 ({@damage 4d10 + 5}) psychic damage. If the target is Large or smaller, it is {@condition grappled} (escape {@dc 14}) and must succeed on a {@dc 17} Intelligence saving throw or be {@condition stunned} until this grapple ends.

**Extract Brain.** {@atk mw} {@hit 9} to hit, reach 5 ft., one {@condition incapacitated} humanoid {@condition grappled} by the ulitharid. {@h}55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, the ulitharid kills the target by extracting and devouring its brain.

**Mind Blast {@recharge 5}.** The ulitharid magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a {@dc 17} Intelligence saving throw or take 31 ({@damage 4d12 + 5}) psychic damage and be {@condition stunned} for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration