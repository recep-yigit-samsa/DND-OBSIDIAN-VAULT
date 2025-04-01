# Ancient Wind Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Wind Dragon | Dragon | 21 | 351 (19d20 + 152) | 20 | walk: 30 ft., fly: {'number': 120, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 9 | - | - |
| Claw | 2d6 + 9 | - | - |
| Tail | 2d8 + 9 | - | - |
| Frightful Presence | - | 20 | - |
| Tempest Breath {@recharge 5} | 8d8 + 8d8 | 23 | - |


**Multiattack.** The wind dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}20 ({@damage 2d10 + 9}) piercing damage.

**Claw.** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. it: 16 ({@damage 2d6 + 9}) slashing damage.

**Tail.** {@atk mw} {@hit 16} to hit, reach 20 ft., one target. {@h}18 ({@damage 2d8 + 9}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 20} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Tempest Breath {@recharge 5}.** The dragon exhales a blast of stormy wind in a 90-foot cone. Each creature in that area must make a {@dc 23} Strength saving throw. On a failure, a creature takes 36 ({@damage 8d8}) bludgeoning damage and 36 ({@damage 8d8}) lightning damage and is pushed up to 45 feet away from the dragon and knocked {@condition prone}. On a success, a creature takes half the damage and isn't pushed or knocked {@condition prone}. Nonmagical flames in the area are extinguished.

^Tags: #monster #type_dragon