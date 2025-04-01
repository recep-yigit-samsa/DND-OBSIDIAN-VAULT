# Cradle of the Cloud Scion

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cradle of the Cloud Scion | Elemental | 26 | 624 (32d20 + 288) | 19 | walk: 0 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d10 + 9 + 3d12 | - | - |
| Wind Javelin | 4d8 + 9 + 3d6 | 25 | - |
| Vortex {@recharge 5} | 11d12 | 25 | - |


**Multiattack.** The cradle makes three Slam or Wind Javelin attacks in any combination.

**Slam.** {@atk mw} {@hit 17} to hit, reach 20 ft., one target. {@h}31 ({@damage 4d10 + 9}) bludgeoning damage plus 19 ({@damage 3d12}) thunder damage.

**Wind Javelin.** {@atk rw} {@hit 17} to hit, range 120 ft., one target. {@h}27 ({@damage 4d8 + 9}) bludgeoning damage plus 10 ({@damage 3d6}) thunder damage, and the target must succeed on a {@dc 25} Strength saving throw or have the {@condition prone} condition.

**Vortex {@recharge 5}.** The cradle conjures a vortex of wind at a point it can see within 90 feet of itself. The wind vortex is a 30-foot-radius, 100-foot-high cylinder centered on that point. Each creature other than the cradle in that area must make a {@dc 25} Dexterity saving throw. On a failed save, a creature takes 71 ({@damage 11d12}) bludgeoning damage and has the {@condition restrained} condition within the vortex. On a successful save, a creature takes half as much damage and is pushed to the nearest unoccupied space outside the cylinder. The vortex lasts until the start of the cradle's next turn. A creature with the {@condition restrained} condition falls {@condition prone} when the vortex ends. A creature with the {@condition restrained} condition can use its action to try to escape the vortex. The creature makes a {@dc 19} Strength ({@skill Athletics}) or Dexterity ({@skill Acrobatics}) check. On a successful check, the creature escapes and moves {@dice 3d6 × 10} feet away from the vortex in a random direction.

^Tags: #monster #type_elemental