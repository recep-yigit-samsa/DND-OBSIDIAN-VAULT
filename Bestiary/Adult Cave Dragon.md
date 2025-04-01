# Adult Cave Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Cave Dragon | Dragon | 19 | 270 (20d12 + 140) | 18 | walk: 40 ft., burrow: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 8 + 3d6 | - | - |
| Claw | 2d6 + 8 | - | - |
| Tail | 2d8 + 8 | - | - |
| Frightful Presence | - | 17 | - |
| Poison Breath {@recharge 5} | 16d6 | 21 | - |


**Multiattack.** The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage plus 10 ({@damage 3d6}) poison damage.

**Claw.** {@atk mw} {@hit 14} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d6 + 8}) slashing damage.

**Tail.** {@atk mw} {@hit 14} to hit, reach 15 ft., one target. {@h}17 ({@damage 2d8 + 8}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 17} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Poison Breath {@recharge 5}.** The dragon exhales a cone of black, poisonous gas in a 60-foot cone. Each target in that area must make a {@dc 21} Constitution saving throw. On a failure, a creature takes 56 ({@damage 16d6}) poison damage and is {@condition poisoned} until it finishes a short rest. A creature can repeat the saving throw at the end of each hour, ending the effect on itself on a success.

^Tags: #monster #type_dragon