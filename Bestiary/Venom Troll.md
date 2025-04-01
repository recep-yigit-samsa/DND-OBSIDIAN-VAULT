# Venom Troll

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Venom Troll | Giant | 7 | 94 (9d10 + 45) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 4 + 1d8 | - | - |
| Claws | 2d6 + 4 + 1d8 | - | - |
| Venom Spray {@recharge} | 2d6 + 4d8 | 16 | - |


**Multiattack.** The troll makes three attacks: one with its bite and two with its claws.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d6 + 4}) piercing damage plus 4 ({@damage 1d8}) poison damage, and the creature is {@condition poisoned} until the start of the troll's next turn.

**Claws.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage plus 4 ({@damage 1d8}) poison damage.

**Venom Spray {@recharge}.** The troll slices itself with a claw, releasing a spray of poison in a 15-foot cube. The troll takes 7 ({@damage 2d6}) slashing damage (this damage can't be reduced in any way). Each creature in the area must make a {@dc 16} Constitution saving throw. On a failed save, a creature takes 18 ({@damage 4d8}) poison damage and is {@condition poisoned} for 1 minute. On a successful save, the creature takes half as much damage and isn't {@condition poisoned}. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_giant