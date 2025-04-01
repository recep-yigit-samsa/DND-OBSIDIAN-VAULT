# Thuellai

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Thuellai | Elemental | 12 | 161 (14d12 + 70) | 17 | walk: 0 ft., fly: {'number': 100, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Icy Claw | 2d8 + 6 + 3d6 | - | - |
| Freezing Breath {@recharge 5} | 14d6 | 17 | - |


**Multiattack.** The thuellai makes three Icy Claw attacks.

**Icy Claw.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d8 + 6}) slashing damage plus 10 ({@damage 3d6}) cold damage.

**Freezing Breath {@recharge 5}.** The thuellai exhales an icy blast in a 60-foot cone. Each creature in the area must make a {@dc 17} Dexterity saving throw, taking 49 ({@damage 14d6}) cold damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_elemental