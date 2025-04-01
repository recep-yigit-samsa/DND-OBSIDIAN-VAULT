# Young Cave Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Cave Dragon | Dragon | 9 | 189 (18d10 + 90) | 17 | walk: 40 ft., burrow: 20 ft., climb: 20 ft., fly: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 6 + 2d6 | - | - |
| Claw | 2d6 + 6 | - | - |
| Poison Breath {@recharge 5} | 12d6 | 17 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage plus 7 ({@damage 2d6}) poison damage.

**Claw.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage.

**Poison Breath {@recharge 5}.** The dragon exhales a cone of black, poisonous gas in a 30-foot cone. Each creature in that area must make a {@dc 17} Constitution saving throw. On a failure, a creature takes 42 ({@damage 12d6}) poison damage and is {@condition poisoned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition poisoned}. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_dragon