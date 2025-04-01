# Geryon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Geryon | Unknown | 22 | 300 (24d12 + 144) | 19 | walk: 30 ft., fly: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claws | 4d6 + 9 + 6d8 | 24 | - |
| Stinger | 2d4 + 9 + 2d12 | 21 | - |
| Teleport | - | - | - |


**Multiattack.** Geryon makes two attacks: one with his claws and one with his stinger.

**Claws.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}23 ({@damage 4d6 + 9}) slashing damage. If the target is Large or smaller, it is {@condition grappled} ({@dc 24}) and is {@condition restrained} until the grapple ends. Geryon can grapple one creature at a time. If the target is already {@condition grappled} by Geryon, the target takes an extra 27 ({@damage 6d8}) slashing damage.

**Stinger.** {@atk mw} {@hit 16} to hit, reach 20 ft., one creature. {@h}14 ({@damage 2d4 + 9}) piercing damage, and the target must succeed on a {@dc 21} Constitution saving throw or take 13 ({@damage 2d12}) poison damage and become {@condition poisoned} until it finishes a short or long rest. The target's hit point maximum is reduced by an amount equal to half the poison damage it takes. If its hit point maximum drops to 0, it dies. This reduction lasts until the {@condition poisoned} condition is removed.

**Teleport.** Geryon magically teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.

^Tags: #monster #type_unknown