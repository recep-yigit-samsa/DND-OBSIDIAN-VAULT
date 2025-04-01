# Rotting Wind

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Rotting Wind | Undead | 6 | 110 (13d10 + 39) | 15 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 14 | - |
| Wind of Decay | 2d6 + 5 + 3d6 | - | - |


**Multiattack.** The rotting wind makes two Wind of Decay attacks. If both attacks hit one creature, the target must succeed on a {@dc 14} Constitution saving throw or contract the tomb rot disease (see the Tomb Rot trait).

**Wind of Decay.** {@atk mw} {@hit 8} to hit, reach 0 ft., one target in the rotting wind's space. {@h}12 ({@damage 2d6 + 5}) bludgeoning damage plus 10 ({@damage 3d6}) necrotic damage.

^Tags: #monster #type_undead