# Spectral Cloud

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Spectral Cloud | Undead | 13 | 189 (18d12 + 72) | 11 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Spectral Touch | 3d8 + 7 + 3d6 | 20 | - |
| Chilling Winds {@recharge 5} | 7d10 | 20 | - |


**Multiattack.** The spectral cloud makes two Spectral Touch attacks.

**Spectral Touch.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}20 ({@damage 3d8 + 7}) force damage plus 10 ({@damage 3d6}) necrotic damage. If the target is a creature, it must succeed on a {@dc 20} Constitution saving throw, or its hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A Humanoid slain by this attack immediately rises as a miniature spectral cloud (use the {@creature specter} stat block in the Monster Manual). The miniature spectral cloud acts as an ally of its creator but isn't under its control.

**Chilling Winds {@recharge 5}.** The spectral cloud emits intensely cold wind in a 60-foot line that is 10 feet wide. Each creature in that area must make a {@dc 20} Constitution saving throw. On a failed save, a creature takes 38 ({@damage 7d10}) cold damage and has the {@condition incapacitated} condition for 1 minute. The affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, a creature takes half as much damage only. If a creature's saving throw is successful or the effect ends for it, that creature is immune to this spectral cloud's Chilling Winds for the next 24 hours.

^Tags: #monster #type_undead