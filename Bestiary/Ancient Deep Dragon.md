# Ancient Deep Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Deep Dragon | Dragon | {'cr': '18', 'lair': '19'} | 201 (13d20 + 65) | 20 | walk: 40 ft., burrow: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 6 + 2d10 | - | - |
| Claw | 2d6 + 6 | - | - |
| Tail | 1d8 + 6 | 20 | - |
| Change Shape | - | - | - |
| Nightmare Breath {@recharge 5} | 9d10 | 19 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage plus 11 ({@damage 2d10}) poison damage.

**Claw.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage.

**Tail.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}10 ({@damage 1d8 + 6}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 20} Strength saving throw or be knocked {@condition prone}.

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses its action to end it.

**Nightmare Breath {@recharge 5}.** The dragon exhales a cloud of spores in a 90-foot cone. Each creature in that area must make a {@dc 19} Wisdom saving throw. On a failed save, the creature takes 49 ({@damage 9d10}) psychic damage, and it is {@condition frightened} of the dragon for 1 minute. On a successful save, the creature takes half as much damage with no additional effects. A {@condition frightened} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_dragon