# Nightwalker

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nightwalker | Undead | 20 | 297 (22d12 + 154) | 14 | walk: 40 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Enervating Focus | 5d8 + 6 | 21 | - |
| Finger of Doom {@recharge} | 4d12 | 21 | - |


**Multiattack.** The nightwalker uses Enervating Focus twice, or it uses Enervating Focus and Finger of Doom, if available.

**Enervating Focus.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}28 ({@damage 5d8 + 6}) necrotic damage. The target must succeed on a {@dc 21} Constitution saving throw or its hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest.

**Finger of Doom {@recharge}.** The nightwalker points at one creature it can see within 300 feet of it. The target must succeed on a {@dc 21} Wisdom saving throw or take 26 ({@damage 4d12}) necrotic damage and become {@condition frightened} until the end of the nightwalker's next turn. While {@condition frightened} in this way, the creature is also {@condition paralyzed}. If a target's saving throw is successful, the target is immune to the nightwalker's Finger of Doom for the next 24 hours.

^Tags: #monster #type_undead