# Cosmic Horror

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cosmic Horror | Aberration | 18 | 280 (16d20 + 112) | 15 | walk: 50 ft., fly: 100 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d6 + 8 | - | - |
| Tentacle | 3d6 + 8 | 18 | - |
| Psychic Whispers {@recharge 5} | 6d10 | 21 | - |


**Multiattack.** The horror makes one Bite attack and two Tentacle attacks.

**Bite.** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}22 ({@damage 4d6 + 8}) piercing damage.

**Tentacle.** {@atk mw} {@hit 14} to hit, reach 30 ft., one target. {@h}18 ({@damage 3d6 + 8}) force damage, and if the target is a creature, it is {@condition grappled} (escape {@dc 18}). Until this grapple ends, the horror can't use this tentacle against other targets. The horror has {@dice 1d8 + 1} tentacles, each of which can grapple one target.

**Psychic Whispers {@recharge 5}.** The horror emits dreadful whispers in a 60-foot-radius sphere centered on itself. Each creature in the sphere that isn't an Aberration must make a {@dc 21} Wisdom saving throw, taking 33 ({@damage 6d10}) psychic damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_aberration