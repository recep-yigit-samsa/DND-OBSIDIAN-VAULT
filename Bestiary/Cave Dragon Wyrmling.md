# Cave Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cave Dragon Wyrmling | Dragon | 2 | 52 (7d8 + 21) | 16 | walk: 30 ft., burrow: 20 ft., fly: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d10 + 4 + 1d6 | - | - |
| Poison Breath {@recharge 5} | 4d6 | 13 | - |


**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d10 + 4}) piercing damage plus 3 ({@damage 1d6}) poison damage.

**Poison Breath {@recharge 5}.** The dragon exhales a cone of black, poisonous gas in a 15-foot cone. Each creature in that area must make a {@dc 13} Constitution saving throw. On a failure, a creature takes 14 ({@damage 4d6}) poison damage and is {@condition poisoned} until the end of its next turn. On a success, a creature takes half the damage and isn't {@condition poisoned}.

^Tags: #monster #type_dragon