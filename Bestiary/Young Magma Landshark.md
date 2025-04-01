# Young Magma Landshark

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Magma Landshark | Elemental | 9 | 105 (10d10 + 50) | 16 | walk: 40 ft., burrow: 40 ft., swim: {'number': 40, 'condition': '(lava only)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 4d12 + 5 + 4d6 | - | - |
| Deadly Leap | 4d6 + 5 + 4d6 | 16 | - |


**Bite.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}31 ({@damage 4d12 + 5}) piercing damage, and 14 ({@damage 4d6}) fire damage.

**Deadly Leap.** If the landshark {@quickref jumping|PHB|4|0|jumps} at least 15 feet as part of its movement, it can then use this action to land on its feet in a space that contains one or more other creatures. Each of those creatures must succeed on a {@dc 16} Strength or Dexterity {@quickref saving throws|PHB|2|1|saving throw} (target's choice) or be knocked {@condition prone} and take 19 ({@damage 4d6 + 5}) bludgeoning damage plus 14 ({@damage 4d6}) fire damage. On a successful save, the creature takes only half the damage, isn't knocked {@condition prone}, and is pushed 5 feet out of the landshark's space into an unoccupied space of the creature's choice. If no unoccupied space is within range, the creature instead falls {@condition prone} in the land-shark's space.

^Tags: #monster #type_elemental