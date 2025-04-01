# Blaze

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Blaze | Elemental | 5 | 75 (10d8 + 30) | 13 | walk: 20 ft., fly: {'number': 20, 'condition': '(vertical movement only; hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Fiery Doom | 1d10 + 3 + 1d6 | - | - |


**Multiattack.** The blaze makes three Fiery Doom attacks.

**Fiery Doom.** {@atk ms,rs} {@hit 6} to hit; reach 5 ft. or ranged 60 ft., one target. {@h}8 ({@damage 1d10 + 3}) fire damage, and the target catches fire if it's a creature or a flammable object. Until a creature takes an action to extinguish the fire, the burning target takes 3 ({@damage 1d6}) fire damage at the end of each of its turns.

^Tags: #monster #type_elemental