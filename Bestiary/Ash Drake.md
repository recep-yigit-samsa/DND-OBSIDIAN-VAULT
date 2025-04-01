# Ash Drake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ash Drake | Dragon | 4 | 117 (18d6 + 54) | 16 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 2 + 1d6 | - | - |
| Claw | 2d6 + 2 | - | - |
| Ash Cloud {@recharge} | - | 13 | - |
| Ash Breath {@recharge 5} | 4d6 | 13 | - |


**Multiattack.** The drake makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d6 + 2}) piercing damage plus 3 ({@damage 1d6}) fire damage.

**Claw.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d6 + 2}) slashing damage.

**Ash Cloud {@recharge}.** The ash drake beats its wings, filling the area within 10 feet of it with ash for 1 minute. The ash spreads around corners, and its area is heavily obscured. Each creature that isn't an ash drake and that enters the cloud for the first time on its turn or starts its turn there must succeed on a {@dc 13} Constitution saving throw or become {@condition blinded} until the end of its next turn. The ash moves with the drake, remaining centered on it for the duration.

**Ash Breath {@recharge 5}.** The ash drake spews blistering hot, choking ash in a 30-foot cone. Each creature in the area must make a {@dc 13} Dexterity saving throw. On a failure, a creature takes 14 ({@damage 4d6}) fire damage and is {@condition poisoned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition poisoned}. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_dragon