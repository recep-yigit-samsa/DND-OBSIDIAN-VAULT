# Ancient Sea Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Sea Dragon | Dragon | 23 | 518 (28d20 + 224) | 22 | walk: 40 ft., fly: 80 ft., swim: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 9 + 4d6 | - | - |
| Fin | 2d6 + 9 | - | - |
| Tail | 2d8 + 9 | - | - |
| Frightful Presence | - | 20 | - |
| Tidal Breath {@recharge 5} | 8d10 + 8d10 | 23 | - |


**Multiattack.** The dragon uses its Frightful Presence. It then makes one Bite attack and two Fin attacks.

**Bite.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}20 ({@damage 2d10 + 9}) piercing damage plus 14 ({@damage 4d6}) cold damage.

**Fin.** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d6 + 9}) slashing damage.

**Tail.** {@atk mw} {@hit 16} to hit, reach 20 ft., one target. {@h}18 ({@damage 2d8 + 9}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 20} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Tidal Breath {@recharge 5}.** The dragon exhales a crushing wave of frigid seawater in a 90-foot cone. Each creature in that area must make a {@dc 23} Dexterity saving throw. On a failure, the creature takes 44 ({@damage 8d10}) bludgeoning damage and 44 ({@damage 8d10}) cold damage and is pushed up to 45 feet away from the dragon and knocked {@condition prone}. On a success, the creature takes half the damage and isn't pushed or knocked {@condition prone}.

^Tags: #monster #type_dragon