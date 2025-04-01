# Adult Wind Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Wind Dragon | Dragon | 16 | 187 (15d12 + 90) | 17 | walk: 30 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 7 | - | - |
| Claw | 2d6 + 7 | - | - |
| Tail | 2d8 + 7 | - | - |
| Frightful Presence | - | 17 | - |
| Tempest Breath {@recharge 5} | 6d8 + 6d8 | 19 | - |


**Multiattack.** The wind dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}18 ({@damage 2d10 + 7}) piercing damage.

**Claw.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d6 + 7}) slashing damage.

**Tail.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}16 ({@damage 2d8 + 7}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 17} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Tempest Breath {@recharge 5}.** The dragon exhales a blast of stormy wind in a 60-foot cone. Each creature in that area must make a {@dc 19} Strength saving throw. On a failure, a creature takes 27 ({@damage 6d8}) bludgeoning damage and 27 ({@damage 6d8}) lightning damage and is pushed up to 30 feet away from the dragon and knocked {@condition prone}. On a success, a creature takes half the damage and isn't pushed or knocked {@condition prone}. Unprotected flames, such as torches, in the area are extinguished, and protected flames, such as those in lanterns, have a 75 percent chance of being extinguished.

^Tags: #monster #type_dragon