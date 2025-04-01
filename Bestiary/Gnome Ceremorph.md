# Gnome Ceremorph

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gnome Ceremorph | Aberration | 5 | 58 (13d6 + 13) | 16 | walk: 25 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tentacles | 2d10 + 4 | 9 | - |
| Extract Brain | 10d10 | - | - |
| Laser Pistol | 3d6 + 2 | - | - |
| Mind Blast {@recharge 5} | 4d8 + 4 | 15 | - |


**Tentacles.** {@atk mw} {@hit 7} to hit, reach 5 ft., one creature. {@h}15 ({@damage 2d10 + 4}) psychic damage. If the target is Medium or smaller, it is {@condition grappled} (escape {@dc 9}) and must succeed on a {@dc 15} Intelligence saving throw or be {@condition stunned} until this grapple ends.

**Extract Brain.** {@atk mw} {@hit 7} to hit, reach 5 ft., one {@condition incapacitated} humanoid {@condition grappled} by the ceremorph. {@h}55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, the ceremorph kills the target by extracting and devouring its brain.

**Laser Pistol.** {@atk rw} {@hit 5} to hit, range 40/120 ft., one target. {@h}12 ({@damage 3d6 + 2}) radiant damage.

**Mind Blast {@recharge 5}.** The ceremorph magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a {@dc 15} Intelligence saving throw or take 22 ({@damage 4d8 + 4}) psychic damage and be {@condition stunned} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration