# Gallows Speaker

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gallows Speaker | Undead | 6 | 85 (19d8) | 12 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Foretelling Touch | 2d10 + 4 | - | - |
| Suffering Echoes | 3d12 + 3d8 | 15 | - |


**Foretelling Touch.** {@atk ms} {@hit 7} to hit, reach 5 ft., one creature. {@h}15 ({@damage 2d10 + 4}) psychic damage, and the target must roll a {@dice d4} and subtract the number rolled from the next attack roll or saving throw it makes before the start of the gallows speaker's next turn.

**Suffering Echoes.** The gallows speaker targets a creature it can see within 30 feet of it. The target must make a {@dc 15} Wisdom saving throw. On a failed save, the target takes 19 ({@damage 3d12}) psychic damage, and waves of painful memories leap from the target to up to three other creatures of the gallows speaker's choice that are within 30 feet of the target, each of which takes 13 ({@damage 3d8}) psychic damage.

^Tags: #monster #type_undead