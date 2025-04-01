# Adult Flame Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Flame Dragon | Dragon | 16 | 275 (22d12 + 132) | 19 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 4 + 3d6 | - | - |
| Claw | 2d6 + 4 | - | - |
| Tail | 2d8 + 4 | - | - |
| Frightful Presence | - | 18 | - |
| Fire Breath {@recharge 5} | 16d6 | 19 | - |


**Multiattack.** The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage plus 10 ({@damage 3d6}) fire damage.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage.

**Tail.** {@atk mw} {@hit 9} to hit, reach 15 ft., one target. {@h}13 ({@damage 2d8 + 4}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 18} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Fire Breath {@recharge 5}.** The dragon exhales fire in a 60-foot cone. Each creature in that area must make a {@dc 19} Dexterity saving throw, taking 56 ({@damage 16d6}) fire damage on a failed save, or half as much damage on a successful one. Each creature in that area must also succeed on a {@dc 18} Wisdom saving throw or go on a rampage for 1 minute. A rampaging creature must attack the nearest creature other than the dragon on its turn. If no other creature is near enough to move to and attack, the rampaging creature stalks off in a random direction, seeking a target for its rage. The rampaging creature can repeat the Wisdom saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_dragon