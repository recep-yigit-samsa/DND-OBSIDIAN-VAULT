# Shadow Beast

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shadow Beast | Fey | 7 | 112 (15d8 + 45) | 15 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d8 + 5 + 2d6 | - | - |
| Claw | 1d6 + 5 + 2d6 | - | - |
| Frightful Shadows {@recharge 5} | 12d6 | 15 | - |


**Multiattack.** The shadow beast makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d8 + 5}) piercing damage plus 7 ({@damage 2d6}) necrotic damage.

**Claw.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d6 + 5}) slashing damage plus 7 ({@damage 2d6}) necrotic damage.

**Frightful Shadows {@recharge 5}.** The shadow beast releases a wave of shadows filled with frightening images of eyes, fangs, and other barely seen and terrifying beasts in a 30-foot cone. Each creature in the area must make a {@dc 15} Wisdom saving throw. On a failure, a creature takes 42 ({@damage 12d6}) necrotic damage and is {@condition frightened} for 1 minute. On a success, a creature takes half the damage and isn't {@condition frightened}. A {@condition frightened} creature must take the Dash action and move away from the shadow beast by the safest available route on each of its turns, unless there is nowhere to move. A {@condition frightened} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_fey