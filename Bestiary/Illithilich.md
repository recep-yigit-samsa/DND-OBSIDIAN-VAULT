# Illithilich

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Illithilich | Undead | 22 | 135 (18d8 + 54) | 17 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Paralyzing Touch | 3d6 | 18 | - |
| Tentacles | 3d10 + 5 | 15 | - |
| Extract Brain | 10d10 | - | - |
| Mind Blast {@recharge 5} | 5d8 + 5 | 18 | - |


**Paralyzing Touch.** {@atk ms} {@hit 12} to hit, reach 5 ft., one creature. {@h}10 ({@damage 3d6}) cold damage. The target must succeed on a {@dc 18} Constitution saving throw or be {@condition paralyzed} for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Tentacles.** {@atk mw} {@hit 12} to hit, reach 5 ft., one creature. {@h}21 ({@damage 3d10 + 5}) psychic damage. If the target is Large or smaller, it is {@condition grappled} (escape {@dc 15}) and must succeed on a {@dc 20} Intelligence saving throw or be {@condition stunned} until this grapple ends.

**Extract Brain.** {@atk mw} {@hit 12} to hit, reach 5 ft., one {@condition incapacitated} humanoid {@condition grappled} by the lich. {@h}55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, the lich kills the target by extracting and devouring its brain.

**Mind Blast {@recharge 5}.** The illithilich magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a {@dc 18} Intelligence saving throw or take 27 ({@damage 5d8 + 5}) psychic damage and be {@condition stunned} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_undead