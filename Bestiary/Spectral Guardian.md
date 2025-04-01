# Spectral Guardian

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Spectral Guardian | Undead | 6 | 93 (11d8 + 44) | 14 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 15 | - |
| Spectral Blade | 2d8 + 4 + 2d8 | 14 | - |


**Multiattack.** The spectral guardian makes two Spectral Blade attacks. If both attacks hit one creature, the target must succeed on a {@dc 15} Constitution saving throw or have its hp maximum reduced by the total necrotic damage dealt by both attacks.

**Spectral Blade.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) slashing damage plus 9 ({@damage 2d8}) necrotic damage, and the target must succeed on a {@dc 14} Wisdom saving throw or be {@condition frightened} until the end of its next turn.

^Tags: #monster #type_undead