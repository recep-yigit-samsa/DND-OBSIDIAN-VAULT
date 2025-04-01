# Zodar

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Zodar | Aberration | 16 | 200 (16d8 + 128) | 20 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Crushing Fist | 2d10 + 10 | - | - |
| Forced Teleport | 4d10 | 21 | - |


**Multiattack.** The zodar makes two Crushing Fist attacks. Before or after these attacks, the zodar uses Forced Teleport.

**Crushing Fist.** {@atk mw} {@hit 15} to hit, reach 5 ft., one target. {@h}21 ({@damage 2d10 + 10}) force damage.

**Forced Teleport.** The zodar magically warps space around one creature it can see within 60 feet of itself. The target must make a {@dc 21} Constitution saving throw. On a failed save, the target takes 22 ({@damage 4d10}) force damage, and the zodar teleports it, along with any equipment it's wearing or carrying, up to 60 feet to an unoccupied space that the zodar can see and that can support the target. On a successful save, the target takes half as much damage and isn't teleported.

^Tags: #monster #type_aberration