# Adult Deep Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Deep Dragon | Dragon | {'cr': '11', 'lair': '12'} | 147 (14d12 + 56) | 17 | walk: 40 ft., burrow: 30 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 + 1d10 | - | - |
| Claw | 1d6 + 5 | - | - |
| Tail | 1d8 + 5 | 17 | - |
| Change Shape | - | - | - |
| Nightmare Breath {@recharge 5} | 6d10 | 16 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage plus 5 ({@damage 1d10}) poison damage.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d6 + 5}) slashing damage.

**Tail.** {@atk mw} {@hit 9} to hit, reach 15 ft., one target. {@h}9 ({@damage 1d8 + 5}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 17} Strength saving throw or be knocked {@condition prone}.

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses its action to end it.

**Nightmare Breath {@recharge 5}.** The dragon exhales a cloud of spores in a 60-foot cone. Each creature in that area must make a {@dc 16} Wisdom saving throw. On a failed save, the creature takes 33 ({@damage 6d10}) psychic damage, and it is {@condition frightened} of the dragon for 1 minute. On a successful save, the creature takes half as much damage with no additional effects. A {@condition frightened} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_dragon