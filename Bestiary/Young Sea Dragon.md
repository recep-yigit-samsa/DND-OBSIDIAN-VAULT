# Young Sea Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Sea Dragon | Dragon | 9 | 190 (20d10 + 80) | 18 | walk: 40 ft., fly: 80 ft., swim: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 + 2d6 | - | - |
| Fin | 2d6 + 5 | - | - |
| Tidal Breath {@recharge 5} | 4d10 + 4d10 | 16 | - |


**Multiattack.** The dragon makes one Bite attack and two Fin attacks.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage plus 7 ({@damage 2d6}) cold damage.

**Fin.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage.

**Tidal Breath {@recharge 5}.** The dragon exhales a crushing wave of frigid seawater in a 30-foot cone. Each creature in that area must make a {@dc 16} Dexterity saving throw. On a failure, the creature takes 22 ({@damage 4d10}) bludgeoning damage and 22 ({@damage 4d10}) cold damage and is pushed up to 15 feet away from the dragon and knocked {@condition prone}. On a success, the creature takes half the damage and isn't pushed or knocked {@condition prone}.

^Tags: #monster #type_dragon