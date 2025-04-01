# Steel Predator

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Steel Predator | Construct | 16 | 207 (18d10 + 108) | 20 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 7 | - | - |
| Claw | 2d8 + 7 | - | - |
| Stunning Roar {@recharge 5} | 5d10 | 19 | - |


**Multiattack.** The steel predator makes three attacks: one with its bite and two with its claw.

**Bite.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d6 + 7}) piercing damage.

**Claw.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d8 + 7}) slashing damage.

**Stunning Roar {@recharge 5}.** The steel predator emits a roar in a 60-foot cone. Each creature in that area must make a {@dc 19} Constitution saving throw. On a failed save, a creature takes 27 ({@damage 5d10}) thunder damage, drops everything it's holding, and is {@condition stunned} for 1 minute. On a successful save, a creature takes half as much damage. The {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_construct