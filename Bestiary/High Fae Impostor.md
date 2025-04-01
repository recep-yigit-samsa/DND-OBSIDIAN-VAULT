# High Fae Impostor

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| High Fae Impostor | Fey | 11 | 149 (23d8 + 46) | 15 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Fae Blade | 3d8 + 5 | - | - |
| Vexing Prank | 6d6 | 18 | - |


**Multiattack.** The high fae makes two Fae Blade attacks and uses Vexing Prank once.

**Fae Blade.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}18 ({@damage 3d8 + 5}) force damage.

**Vexing Prank.** The high fae targets one creature it can see within 60 feet of itself with a magical trick. The target must make a {@dc 18} Wisdom saving throw. On a failed save, the target takes 21 ({@damage 6d6}) psychic damage and has the {@condition frightened} condition until the start of the high fae's next turn. On a successful save, the target takes half as much damage only.

^Tags: #monster #type_fey