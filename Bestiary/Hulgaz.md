# Hulgaz

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hulgaz | Unknown | 14 | 190 (20d10 + 80) | 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d8 + 3 | - | - |
| Intoxicating Sting | 1d10 + 3 + 3d6 | 17 | - |
| Brimstone Vapor {@recharge 5} | 7d8 | 17 | - |


**Multiattack.** Hulgaz makes two Claw attacks and one Intoxicating Sting attack.

**Claw.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d8 + 3}) slashing damage.

**Intoxicating Sting.** {@atk mw} {@hit 8} to hit, reach 10 ft., one creature. {@h}8 ({@damage 1d10 + 3}) piercing damage plus 10 ({@damage 3d6}) poison damage, and the target must succeed on a {@dc 17} Wisdom saving throw or have the {@condition charmed} condition until the start of Hulgaz's next turn.

**Brimstone Vapor {@recharge 5}.** Hulgaz exhales a 30-foot cone of noxious, scorching-hot vapor. Each creature in that area must succeed on a {@dc 17} Constitution saving throw or have the {@condition poisoned} condition for 1 minute. While {@condition poisoned} in this way, a creature takes 31 ({@damage 7d8}) fire damage at the start of each of its turns and has disadvantage on Wisdom saving throws. A target can repeat the Constitution saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown