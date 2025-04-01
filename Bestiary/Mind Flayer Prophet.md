# Mind Flayer Prophet

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mind Flayer Prophet | Aberration | 8 | 97 (15d8 + 30) | 17 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tentacles | 2d10 + 5 | 16 | - |
| Extract Brain | 10d10 | - | - |
| Mind Whip {@recharge 5} | 4d8 + 5 | 16 | - |


**Tentacles.** {@atk mw} {@hit 8} to hit, reach 5 ft., one creature. {@h}16 ({@damage 2d10 + 5}) psychic damage. If the target is Medium or smaller, it has the {@condition grappled} condition (escape {@dc 16}) and must succeed on a {@dc 16} Intelligence saving throw or have the {@condition stunned} condition until the grapple ends.

**Extract Brain.** {@atk mw} {@hit 8} to hit, reach 5 ft., one Humanoid {@condition grappled} by the mind flayer. {@h}55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills it by extracting and devouring its brain.

**Mind Whip {@recharge 5}.** The mind flayer lashes out with psychic energy, targeting up to two creatures it can see within 60 feet of itself. Each target must succeed on a {@dc 16} Intelligence saving throw or take 23 ({@damage 4d8 + 5}) psychic damage and have the {@condition stunned} condition for 1 minute. A {@condition stunned} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration