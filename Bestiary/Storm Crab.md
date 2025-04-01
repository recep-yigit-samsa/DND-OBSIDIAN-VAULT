# Storm Crab

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Storm Crab | Monstrosity | 11 | 155 (10d20 + 50) | 18 | walk: 40 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 3d8 + 6 | 16 | - |
| Stinger | 3d10 + 6 | 17 | - |
| Water Jet {@recharge 5} | 6d8 | 17 | - |


**Multiattack.** The crab makes two Claw attacks and one Stinger attack.

**Claw.** {@atk mw} {@hit 10} to hit, reach 15 ft., one target. {@h}19 ({@damage 3d8 + 6}) bludgeoning damage. If the target is a Huge or smaller creature, it has the {@condition grappled} condition (escape {@dc 16}). The crab has four claws, each of which can grapple one target.

**Stinger.** {@atk mw} {@hit 10} to hit, reach 10 ft., one creature. {@h}22 ({@damage 3d10 + 6}) piercing damage, and the target must succeed on a {@dc 17} Constitution saving throw or have the {@condition poisoned} and {@condition paralyzed} conditions for 1 minute. The affected creature can repeat the saving throw at the end of each of its turns, ending both the {@condition poisoned} and {@condition paralyzed} conditions on itself on a success.

**Water Jet {@recharge 5}.** The crab exhales water in a 150-foot line that is 10 feet wide. Each creature in that area must make a {@dc 17} Dexterity saving throw. On a failed save, a creature takes 27 ({@damage 6d8}) bludgeoning damage, is pushed up to 30 feet from the crab, and has the {@condition prone} condition. On a successful save, a creature takes half as much damage only.

^Tags: #monster #type_monstrosity