# Scream Thief

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Scream Thief | Undead | 3 | 52 (8d8 + 16) | 12 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Life Drain | 4d8 | 12 | - |
| Silence the Living {@recharge 5} | 3d12 | - | - |


**Life Drain.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}18 ({@damage 4d8}) necrotic damage. The target must succeed on a {@dc 12} Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

**Silence the Living {@recharge 5}.** The scream thief forces a humanoid within 30 feet of it to make a DC13 Wisdom saving throw. On a failure, the target takes 19 ({@damage 3d12}) psychic damage, is {@condition frightened}, and is unable to vocalize a sound of any kind. The target may repeat the saving throw at the end of its turns to end these effects. On a success the creature takes half as much damage and is not {@condition frightened} or silenced.

^Tags: #monster #type_undead