# Klauth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Klauth | Dragon | 25 | 546 (28d20 + 252) | 22 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 10 + 4d6 | - | - |
| Claw | 2d6 + 10 | - | - |
| Tail | 2d8 + 10 | - | - |
| Frightful Presence | - | 21 | - |
| Fire Breath {@recharge 5} | 26d6 | 24 | - |


**Multiattack.** Klauth can use his Frightful Presence. He then makes three attacks: one with his bite and two with his claws.

**Bite.** {@atk mw} {@hit 17} to hit, reach 15 ft., one target. {@h}21 ({@damage 2d10 + 10}) piercing damage plus 14 ({@damage 4d6}) fire damage.

**Claw.** {@atk mw} {@hit 17} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d6 + 10}) slashing damage.

**Tail.** {@atk mw} {@hit 17} to hit, reach 20 ft., one target. {@h}19 ({@damage 2d8 + 10}) bludgeoning damage.

**Frightful Presence.** Each creature of Klauth's choice that is within 120 feet of Klauth and aware of him must succeed on a {@dc 21} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Klauth's Frightful Presence for the next 24 hours.

**Fire Breath {@recharge 5}.** Klauth exhales fire in a 90-foot cone. Each creature in that area must make a {@dc 24} Dexterity saving throw, taking 91 ({@damage 26d6}) fire damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon