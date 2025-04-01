# Vampiric Mist

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vampiric Mist | Undead | 3 | 30 (4d8 + 12) | 13 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Life Drain | 2d6 + 3 | 13 | - |


**Life Drain.** The mist touches one creature in its space. The target must succeed on a {@dc 13} Constitution saving throw (undead and constructs automatically succeed), or it takes 10 ({@damage 2d6 + 3}) necrotic damage, the mist regains 10 hit points, and the target's hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

^Tags: #monster #type_undead