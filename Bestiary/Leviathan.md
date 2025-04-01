# Leviathan

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Leviathan | Elemental | 20 | 328 (16d20 + 160) | 17 | walk: 40 ft., swim: 120 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 1d10 + 10 + 1d10 | - | - |
| Tail | 1d12 + 10 + 1d12 | - | - |
| Tidal Wave {@recharge} | 6d10 + 5d10 | 24 | - |


**Multiattack.** The leviathan makes two attacks: one with its slam and one with its tail.

**Slam.** {@atk mw} {@hit 16} to hit, reach 20 ft., one target. {@h}15 ({@damage 1d10 + 10}) bludgeoning damage plus 5 ({@damage 1d10}) acid damage.

**Tail.** {@atk mw} {@hit 16} to hit, reach 20 ft., one target. {@h}16 ({@damage 1d12 + 10}) bludgeoning damage plus 6 ({@damage 1d12}) acid damage.

**Tidal Wave {@recharge}.** While submerged, the leviathan magically creates a wall of water centered on itself. The wall is up 250 feet long, up to 250 feet high, and up to 50 feet thick. When the wall appears, all other creatures within its area must each make a {@dc 24} Strength saving throw. A creature takes 33 ({@damage 6d10}) bludgeoning damage on failed save, or half as much damage on a successful one. At the start of each of the leviathan's turns after the wall appears, the wall, along with any other creatures in it, moves 50 feet away from the leviathan. Any Huge or smaller creature inside the wall or whose space the wall enters when it moves must succeed on a {@dc 24} Strength saving throw or take 27 ({@damage 5d10}) bludgeoning damage. A creature takes this damage no more than once on a turn. At the end of each turn the wall moves, the wall's height is reduced by 50 feet, and the damage creatures take from the wall on subsequent rounds is reduced by {@dice 1d10}. When the wall reaches 0 feet in height, the effect ends. A creature caught in the wall can move by swimming. Because of the force of the wave, though, the creature must make a successful {@dc 24} Strength ({@skill Athletics}) check to swim at all during that turn.

^Tags: #monster #type_elemental