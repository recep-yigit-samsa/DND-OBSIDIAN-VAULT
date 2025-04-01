# Gaj

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gaj | Aberration | 4 | 75 (10d10 + 20) | 16 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Mandibles | 2d6 + 3 + 2d6 + 3 | 11 | - |
| Mind-Probing Antennae | 3d10 | 12 | - |
| Paralyze {@recharge} | - | 12 | - |


**Multiattack.** The gaj makes one Mandibles attack and uses Mind-Probing Antennae or Paralyze (if available).

**Mandibles.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}10 ({@damage 2d6 + 3}) slashing damage, and the target is {@condition grappled} (escape {@dc 11}). Until the grapple ends, the target takes 10 ({@damage 2d6 + 3}) slashing damage at the start of each of the gaj's turns. While it is grappling a creature, the gaj can't use its mandibles to attack other creatures.

**Mind-Probing Antennae.** The gaj targets one creature {@condition grappled} by it. The target must make a {@dc 12} Wisdom saving throw. On a failed save, the target takes 16 ({@damage 3d10}) psychic damage, and the gaj magically pulls one piece of information from the target's mind that the gaj wants to know. On a successful save, the target takes half as much damage, and the gaj learns nothing.

**Paralyze {@recharge}.** The gaj magically targets one creature it can see within 60 feet of itself. The target must succeed on a {@dc 12} Wisdom saving throw or be {@condition paralyzed} for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration