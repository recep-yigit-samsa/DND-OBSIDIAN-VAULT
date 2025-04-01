# Arboreal Grappler

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Arboreal Grappler | Aberration | 4 | 90 (12d8 + 36) | 14 | walk: 10 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 3 | - | - |
| Tentacle | 2d6 + 3 | 13 | - |


**Multiattack.** The arboreal grappler makes one Bite attack and two Tentacle attacks.

**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}6 ({@damage 1d6 + 3}) piercing damage.

**Tentacle.** {@atk mw} {@hit 5} to hit, reach 10 ft., one target. {@h}10 ({@damage 2d6 + 3}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 13}). Until this grapple ends, the target is {@condition restrained}. The arboreal grappler has two tentacles, each of which can grapple only one target.

^Tags: #monster #type_aberration