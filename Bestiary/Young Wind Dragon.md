# Young Wind Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Wind Dragon | Dragon | 6 | 123 (13d10 + 52) | 16 | walk: 30 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 | - | - |
| Claw | 2d6 + 5 | - | - |
| Tempest Breath {@recharge 5} | 6d8 | 15 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage.

**Claw.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage.

**Tempest Breath {@recharge 5}.** The dragon exhales a blast of stormy wind in a 30-foot cone. Each creature in that area must make a {@dc 15} Strength saving throw. On a failure, a creature takes 27 ({@damage 6d8}) bludgeoning damage and is pushed up to 15 feet away from the dragon and knocked {@condition prone}. On a success, a creature takes half the damage and isn't pushed or knocked {@condition prone}. Unprotected flames, such as torches, in the area are extinguished, and protected flames, such as those in lanterns, have a 50 percent chance of being extinguished.

^Tags: #monster #type_dragon