# Shemeshka

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shemeshka | Unknown | 14 | 162 (25d8 + 50) | 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Arcane Flux | 7d12 | 18 | - |
| Claw | 2d4 + 5 + 4d6 | - | - |
| Razorvine Tiara | 3d6 + 2d8 | 15 | - |


**Multiattack.** Shemeshka uses Arcane Flux or Spellcasting. She then makes one Claw attack or one attack with her Razorvine Tiara.

**Arcane Flux.** Shemeshka causes a surge of arcane energy to burst around one creature she can see within 120 feet of herself. The target must make a {@dc 18} Dexterity saving throw. On a failed save, the target takes 45 ({@damage 7d12}) force damage and has the {@condition incapacitated} condition until the end of its next turn. On a successful save, the target takes half as much damage only.

**Claw.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d4 + 5}) slashing damage plus 14 ({@damage 4d6}) poison damage.

**Razorvine Tiara.** {@atk mw} {@hit 10} to hit, reach 15 ft., one target. {@h}10 ({@damage 3d6}) slashing damage plus 9 ({@damage 2d8}) necrotic damage. If the target is a creature, it must succeed on a {@dc 15} Constitution saving throw, or its speed is halved and it has disadvantage on attack rolls and saving throws until the end of its next turn.

^Tags: #monster #type_unknown