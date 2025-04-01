# Ancient Amethyst Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Amethyst Dragon | Unknown | {'cr': '23', 'lair': '24'} | 444 (24d20 + 192) | 20 | walk: 40 ft., fly: {'number': 80, 'condition': '(hover)'} ft., swim: 40 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 8 + 3d8 | - | - |
| Claw | 2d6 + 8 | - | - |
| Singularity Breath {@recharge 5} | 14d8 | 23 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 15} to hit, reach 15 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage plus 13 ({@damage 3d8}) force damage.

**Claw.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d6 + 8}) slashing damage.

**Singularity Breath {@recharge 5}.** The dragon creates a shining bead of gravitational force in its mouth, then releases the energy in a 90-foot cone. Each creature in that area must make a {@dc 23} Strength saving throw. On a failed save, the creature takes 63 ({@damage 14d8}) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.

^Tags: #monster #type_unknown