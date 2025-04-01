# Drowned Master

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Drowned Master | Undead | 9 | 157 (21d8 + 63) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Greatsword | 2d6 + 3 + 4d6 | 12 | - |
| Life-Draining Tentacle | 2d6 + 3 | 15 | - |
| Necrotic Ink {@recharge 5} | 6d8 | 15 | - |


**Multiattack.** The drowned master makes two attacks: one with its greatsword and one with its Life-Draining Tentacle.

**Greatsword.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) slashing damage plus 14 ({@damage 4d6}) cold damage, and the target must succeed on a {@dc 12} Constitution saving throw or contract {@disease bluerot|GoS} (see the "Bluerot" in notes).

**Life-Draining Tentacle.** {@atk mw} {@hit 7} to hit, reach 15 ft., one target. {@h}10 ({@damage 2d6 + 3}) necrotic damage. The target must succeed on a {@dc 15} Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this effect reduces its hit point maximum to 0. This reduction lasts until the target finishes a long rest. On a failed save, the target also contracts bluerot (see the "Bluerot" in notes).

**Necrotic Ink {@recharge 5}.** The drowned master discharges foul ink in front of itself in a 30-foot cone. Each creature caught in the ink must make a {@dc 15} Constitution saving throw, taking 27 ({@damage 6d8}) necrotic damage on a failed save or half as much damage on a successful one. A creature that fails this saving throw is {@condition blinded} until the end of its next turn and contracts bluerot (see the "Bluerot" in notes).

^Tags: #monster #type_undead