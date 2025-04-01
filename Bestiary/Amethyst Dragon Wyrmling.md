# Amethyst Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Amethyst Dragon Wyrmling | Unknown | 4 | 75 (10d8 + 30) | 17 | walk: 30 ft., fly: {'number': 60, 'condition': '(hover)'} ft., swim: 30 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d10 + 4 + 1d8 | - | - |
| Singularity Breath {@recharge 5} | 5d8 | 13 | - |


**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d10 + 4}) piercing damage plus 4 ({@damage 1d8}) force damage.

**Singularity Breath {@recharge 5}.** The dragon creates a shining bead of gravitational force in its mouth, then releases the energy in a 15-foot cone. Each creature in that area must make a {@dc 13} Strength saving throw. On a failed save, the creature takes 22 ({@damage 5d8}) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.

^Tags: #monster #type_unknown