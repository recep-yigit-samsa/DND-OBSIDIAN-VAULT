# Ancient Cave Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Cave Dragon | Dragon | 25 | 507 (26d20 + 234) | 20 | walk: 40 ft., burrow: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 10 + 4d6 | - | - |
| Claw | 2d6 + 10 | - | - |
| Tail | 2d8 + 10 | - | - |
| Frightful Presence | - | 20 | - |
| Poison Breath {@recharge 5} | 26d6 | 25 | - |


**Multiattack.** The dragon uses its Frightful Presence. It then makes three attacks: one with its Bite and two with its Claws.

**Bite.** {@atk mw} {@hit 18} to hit, reach 15 ft., one target. {@h}21 ({@damage 2d10 + 10}) piercing damage plus 14 ({@damage 4d6}) poison damage.

**Claw.** {@atk mw} {@hit 18} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d6 + 10}) slashing damage.

**Tail.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}19 ({@damage 2d8 + 10}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 20} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Poison Breath {@recharge 5}.** The dragon exhales a cone of black, poisonous gas in a 90-foot cone. Each target in that area must make a {@dc 25} Constitution saving throw. On a failure, a creature takes 91 ({@damage 26d6}) poison damage and is {@condition poisoned} until cured by the {@spell greater restoration} spell or similar magic. On a success, a creature takes half the damage and isn't {@condition poisoned}.

^Tags: #monster #type_dragon