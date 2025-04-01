# Snow Queen

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Snow Queen | Fey | 16 | 182 (28d8 + 56) | 17 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d6 + 4 + 2d6 | - | - |
| Ice Bolt | 2d8 + 4 + 2d6 | - | - |
| Cold Snap {@recharge 5} | 12d6 | 18 | - |


**Multiattack.** The Snow Queen makes two Claw or Ice Bolt attacks.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage plus 7 ({@damage 2d6}) cold damage.

**Ice Bolt.** {@atk rs} {@hit 10} to hit, range 120 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage plus 7 ({@damage 2d6}) cold damage. The target's speed is reduced by 10 feet until the end of its next turn.

**Cold Snap {@recharge 5}.** The Snow Queen causes the temperature around her to drop dramatically. Each creature without 30 feet of the Snow Queen must make a {@dc 18} Constitution saving throw. On a failure, a creature takes 42 ({@damage 12d6}) cold damage and suffers one level of {@condition exhaustion}. On a success, a creature takes half the damage and doesn't suffer {@condition exhaustion}. A creature that is immune to cold damage doesn't suffer {@condition exhaustion}, even if it fails the saving throw. A creature that fails the saving throw by 5 or more is {@condition petrified} in ice for 1 minute. A {@condition petrified} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A {@condition petrified} creature that takes fire damage has advantage on the saving throw to end the effect.

^Tags: #monster #type_fey