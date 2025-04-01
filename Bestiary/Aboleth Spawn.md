# Aboleth Spawn

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Aboleth Spawn | Aberration | 5 | 93 (11d8 + 44) | 14 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Spear | 1d6 + 4 + 1d8 + 4 | - | - |
| Tentacle | 2d8 | 14 | - |
| Psychic Lash | 4d8 | - | - |


**Multiattack.** The spawn makes one Spear attack, two Tentacle attacks, and one Psychic Lash attack.

**Spear.** {@atk mw,rw} {@hit 7} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}7 ({@damage 1d6 + 4}) piercing damage, or 8 ({@damage 1d8 + 4}) piercing damage when used with two hands to make a melee attack.

**Tentacle.** {@atk mw} {@hit 7} to hit, reach 10 ft., one creature. {@h}The target is {@condition grappled} (escape {@dc 14}) and takes 9 ({@damage 2d8}) psychic damage at the start of each of its turns until the grapple ends. The spawn has four tentacles, each of which can grapple one creature.

**Psychic Lash.** {@atk rs} {@hit 7} to hit, range 120 ft., one creature. {@h}18 ({@damage 4d8}) psychic damage.

^Tags: #monster #type_aberration