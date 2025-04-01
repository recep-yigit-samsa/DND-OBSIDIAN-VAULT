# High Fae Kindguard

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| High Fae Kindguard | Fey | 12 | 156 (24d8 + 48) | 17 | walk: 40 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Fae Claymore | 4d6 + 6 | - | - |
| Tripping Feint | - | 18 | - |


**Multiattack.** The high fae makes two Fae Claymore attacks and uses Tripping Feint.

**Fae Claymore.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}20 ({@damage 4d6 + 6}) force damage, and the target's speed is reduced by 10 feet, to a minimum speed of 5 feet. The reduction lasts until the start of the high fae's next turn.

**Tripping Feint.** The high fae targets one Large or smaller creature it can see within 10 feet of itself. The target must succeed on a {@dc 18} Dexterity saving throw or have the {@condition prone} condition.

^Tags: #monster #type_fey