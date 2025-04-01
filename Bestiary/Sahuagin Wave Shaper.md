# Sahuagin Wave Shaper

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sahuagin Wave Shaper | Unknown | 5 | 60 (11d8 + 11) | 14 | walk: 30 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 1 + 3d8 | - | - |
| Claws | 2d8 + 1 + 3d8 | - | - |
| Whirlpool (1/Day) | 2d8 + 2d8 | 14 | Half Damage ✅ |


**Multiattack.** The wave shaper makes two attacks: one with its bite and one with its claws.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d8 + 1}) piercing damage plus 13 ({@damage 3d8}) cold damage.

**Claws.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d8 + 1}) slashing damage plus 13 ({@damage 3d8}) cold damage.

**Whirlpool (1/Day).** The wave shaper targets a body of water at least 50 feet square and 25 feet deep, causing a whirlpool to form in the center of the area. The whirlpool forms a vortex that is 5 feet wide at the base, up to 50 feet wide at the top, 25 feet tall, and lasts for 1 minute or until the wave shaper is {@condition incapacitated}. Any creature or object in the water and within 25 feet of the vortex is pulled 10 feet toward it. A creature can swim away from the vortex by succeeding on a {@dc 14} Strength ({@skill Athletics}) check. When a creature enters the vortex for the first time on a turn or starts its turn there, it must make a {@dc 14} Strength saving throw. On a failed save, the creature takes 9 ({@damage 2d8}) bludgeoning damage and is caught in the vortex until it ends. On a success, the creature takes half damage and isn't caught in the vortex. A creature caught in the vortex can use its action to try to swim away from the vortex as described above, but it has disadvantage on the Strength ({@skill Athletics}) check to do so. The first time each turn that an object enters the vortex, the object takes 9 ({@damage 2d8}) bludgeoning damage. This damage occurs each round it remains in the vortex.

^Tags: #monster #type_unknown