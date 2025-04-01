# Hellwasp

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hellwasp | Fiend | 5 | 52 (8d10 + 8) | 19 | walk: 10 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Sting | 1d8 + 4 + 2d6 | 12 | - |
| Sword Talons | 2d6 + 4 | - | - |


**Multiattack.** The hellwasp makes two attacks: one with its sting and one with its sword talons.

**Sting.** {@atk mw} {@hit 7} to hit, reach 5 ft., one creature. {@h}8 ({@damage 1d8 + 4}) piercing damage plus 7 ({@damage 2d6}) fire damage, and the target must succeed on a {@dc 12} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned} in this way, the target is also {@condition paralyzed}. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Sword Talons.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage.

^Tags: #monster #type_fiend