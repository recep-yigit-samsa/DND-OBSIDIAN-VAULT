# Adult Amethyst Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Amethyst Dragon | Unknown | {'cr': '16', 'lair': '17'} | 229 (17d12 + 119) | 19 | walk: 40 ft., fly: {'number': 80, 'condition': '(hover)'} ft., swim: 40 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 7 + 2d8 | - | - |
| Claw | 1d8 + 7 | - | - |
| Singularity Breath {@recharge 5} | 10d8 | 20 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}18 ({@damage 2d10 + 7}) piercing damage plus 9 ({@damage 2d8}) force damage.

**Claw.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}11 ({@damage 1d8 + 7}) slashing damage.

**Singularity Breath {@recharge 5}.** The dragon creates a shining bead of gravitational force in its mouth, then releases the energy in a 90-foot cone. Each creature in that area must make a {@dc 20} Strength saving throw. On a failed save, the creature takes 45 ({@damage 10d8}) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.

^Tags: #monster #type_unknown