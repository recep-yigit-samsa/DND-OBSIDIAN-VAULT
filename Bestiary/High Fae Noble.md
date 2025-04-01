# High Fae Noble

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| High Fae Noble | Fey | 13 | 175 (27d8 + 54) | 17 | walk: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Fae Blade | 3d8 + 7 | - | - |
| Stunning Soliloquy {@recharge 5} | - | 19 | - |


**Multiattack.** The high fae makes two Fae Blade attacks. It can replace one of these attacks with Stunning Soliloquy if available.

**Fae Blade.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}20 ({@damage 3d8 + 7}) force damage.

**Stunning Soliloquy {@recharge 5}.** The high fae unleashes a string of magical words. Each creature of the high fae's choice within 30 feet of itself must succeed on a {@dc 19} Wisdom saving throw or have the {@condition stunned} condition for 1 minute. A {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_fey