# Miasmorne

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Miasmorne | Monstrosity | 16 | 230 (20d12 + 100) | 19 | walk: 20 ft., burrow: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 6 + 2d6 | 18 | - |
| Flechette | 3d6 + 6 | - | - |
| Flechette Spray {@recharge 5} | 6d6 | 19 | - |
| Acidic Secretion (1/Day) | 4d12 | 19 | - |


**Multiattack.** The miasmorne makes three attacks using Bite, Flechette or a combination of the two.

**Bite.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}22 ({@damage 3d10 + 6}) bludgeoning damage plus 7 ({@damage 2d6}) acid damage. If the target is a Large or smaller creature, it has the {@condition grappled} condition (escape {@dc 18}). The miasmorne can't make Bite attacks while a creature is {@condition grappled} in this way.

**Flechette.** {@atk rw} {@hit 11} to hit, range 60/120 ft., one target. {@h}16 ({@damage 3d6 + 6}) acid damage.

**Flechette Spray {@recharge 5}.** The miasmorne launches flechettes from its fins in a 90-foot cone in front of it. All creatures in the cone must make a {@dc 19} Dexterity saving throw, taking 21 ({@damage 6d6}) acid damage on a failed save, or half as much damage on a successful one.

**Acidic Secretion (1/Day).** The miasmorne secretes an acidic solution, then sprays it around itself. All creatures in a 20-foot-radius sphere, centered on the miasmorne, must make a {@dc 19} Dexterity saving throw. Targets take 26 ({@damage 4d12}) acid damage on a failed save, or half as much damage on a successful one. All nonmagical metals within the radius that aren't being carried, as well as nonmagical metal items carried or worn by creatures that failed the save, are destroyed.

^Tags: #monster #type_monstrosity