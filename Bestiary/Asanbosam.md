# Asanbosam

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Asanbosam | Aberration | 5 | 102 (12d10 + 36) | 14 | walk: 40 ft., climb: 15 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 4 + 2d10 | 14 | - |
| Claws | 3d10 + 4 | 14 | - |


**Multiattack.** The asanbosam makes one Bite attack and one Claws attack.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage. If the target is a creature, it must succeed on a {@dc 14} Constitution saving throw or take 11 ({@damage 2d10}) poison damage and contract a disease. Until the disease ends, the creature is {@condition poisoned}. Every 24 hours that elapse, the infected creature must repeat the saving throw. On a success, the disease ends. On a failure, the creature's hp maximum is reduced by 5 ({@dice 1d10}). This reduction lasts until the disease ends. The target dies if its hp maximum is reduced to 0.

**Claws.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}20 ({@damage 3d10 + 4}) piercing damage, and the target is {@condition grappled} (escape {@dc 14}). Until this grapple ends, the target is {@condition restrained}, and the asanbosam can't use its Claws on another target. If the target is a creature, it must succeed on a {@dc 14} Constitution saving throw or contract the disease described in the Bite attack.

^Tags: #monster #type_aberration