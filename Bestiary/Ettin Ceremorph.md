# Ettin Ceremorph

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ettin Ceremorph | Aberration | 8 | 104 (11d10 + 44) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d8 + 4 | - | - |
| Tentacles | 2d10 + 4 | 14 | - |
| Extract Brain | 10d10 | - | - |
| Mind Bolt (3/Day) | 2d12 + 4 | 15 | - |


**Multiattack.** The ceremorph makes one Slam attack and one Tentacles attack. The ceremorph can replace one of the attacks with a Mind Bolt attack, if available.

**Slam.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}22 ({@damage 4d8 + 4}) bludgeoning damage.

**Tentacles.** {@atk mw} {@hit 7} to hit, reach 10 ft., one creature. {@h}15 ({@damage 2d10 + 4}) psychic damage. If the target is Large or smaller, it has the {@condition grappled} condition (escape {@dc 14}) and must succeed on a {@dc 15} Intelligence saving throw or have the {@condition stunned} condition until this grapple ends.

**Extract Brain.** {@atk mw} {@hit 7} to hit, reach 5 ft., one {@condition incapacitated} Humanoid {@condition grappled} by the ceremorph. {@h}55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, the ceremorph kills the target by extracting and devouring its brain.

**Mind Bolt (3/Day).** {@atk rs} {@hit 7} to hit, range 120 ft., one creature. {@h}17 ({@damage 2d12 + 4}) psychic damage, and the target must succeed on a {@dc 15} Intelligence saving throw or have the {@condition stunned} condition until the end of its next turn.

^Tags: #monster #type_aberration