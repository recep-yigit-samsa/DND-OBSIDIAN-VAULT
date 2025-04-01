# Wind Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Wind Dragon Wyrmling | Dragon | 1 | 32 (5d8 + 10) | 15 | walk: 20 ft., fly: {'number': 80, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d10 + 3 | - | - |
| Tempest Breath {@recharge 5} | 2d8 | 12 | - |


**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d10 + 3}) piercing damage.

**Tempest Breath {@recharge 5}.** The dragon exhales a blast of stormy wind in a 15-foot cone. Each creature in that area must make a {@dc 12} Strength saving throw. On a failure, a creature takes 9 ({@damage 2d8}) bludgeoning damage and is pushed up to 5 feet away from the dragon. On a success, a creature takes half the damage and isn't pushed. Unprotected flames, such as torches, in the area are extinguished, and protected flames, such as those in lanterns, have a 50 percent chance of being extinguished.

^Tags: #monster #type_dragon