# Chupacabra

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Chupacabra | Monstrosity | 3 | 45 (6d8 + 18) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d4 + 2 | 13 | - |
| Drain Blood | 1d6 + 2 | 13 | - |


**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}7 ({@damage 2d4 + 2}) piercing damage. If the target is a creature, it must succeed on a {@dc 13} Strength saving throw or be knocked {@condition prone}.

**Drain Blood.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature that is {@condition prone}, {@condition incapacitated}, or {@condition restrained}. {@h}5 ({@damage 1d6 + 2}) necrotic damage. The target must succeed on a {@dc 13} Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken, and the chupacabra regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

^Tags: #monster #type_monstrosity