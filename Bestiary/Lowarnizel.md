# Lowarnizel

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lowarnizel | Unknown | 9 | 168 (16d10 + 80) | 18 | walk: 40 ft., fly: {'number': 80, 'condition': '(hover)'} ft., swim: 40 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 + 1d8 | - | - |
| Claw | 1d8 + 5 | - | - |
| Singularity Breath {@recharge 5} | 8d8 | 17 | - |


**Multiattack.** Lowarnizel makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage plus 4 ({@damage 1d8}) force damage.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d8 + 5}) slashing damage.

**Singularity Breath {@recharge 5}.** Lowarnizel creates a shining bead of gravitational force, then releases the energy in a 30-foot cone. Each creature in that area must make a {@dc 17} Strength saving throw. On a failed save, a creature takes 36 ({@damage 8d8}) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, a creature takes half as much damage only.

^Tags: #monster #type_unknown