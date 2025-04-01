# Fire Giant Forgecaller

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Fire Giant Forgecaller | Unknown | 18 | 312 (25d12 + 150) | 18 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Forge Hammer | 5d6 + 7 + 3d6 | 19 | - |
| Heated Rock | 3d10 + 7 + 3d12 | 21 | - |
| Magma Wave (Requires Fire Rune) | 8d8 | 19 | - |


**Multiattack.** The giant makes three Forge Hammer attacks or two Heated Rock attacks.

**Forge Hammer.** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}24 ({@damage 5d6 + 7}) bludgeoning damage. {@hom}The giant can cause the hammer to emit a burst of heat in a 30-foot-radius sphere centered on the target. Metal objects in that area glow red-hot until the start of the giant's next turn. Any creature in physical contact with a heated object at the start of its turn must make a {@dc 19} Constitution saving throw. On a failed save, the creature takes 10 ({@damage 3d6}) fire damage and has disadvantage on attack rolls until the start of its next turn unless it has immunity to fire damage. The hammer can emit heat in this way only once per turn.

**Heated Rock.** {@atk rw} {@hit 13} to hit, range 60/240 ft., one target. {@h}23 ({@damage 3d10 + 7}) bludgeoning damage plus 19 ({@damage 3d12}) fire damage. If the target is a Large or smaller creature, it must succeed on a {@dc 21} Strength saving throw or have the {@condition prone} condition. After the giant throws the rock, roll a {@dice d6}; on a roll of 3 or lower, the giant has no more rocks to throw.

**Magma Wave (Requires Fire Rune).** The giant emits a wave of magma from its fire rune in a 30-foot cone. Each creature in that area must make a {@dc 19} Dexterity saving throw. On a failed save, a creature takes 36 ({@damage 8d8}) fire damage and has the {@condition restrained} condition. As an action, a creature can make a {@dc 19} Strength ({@skill Athletics}) check, freeing itself or a creature within its reach from the rock on a success. The rock restraining each creature has AC 17; 20 hit points; and immunity to fire, poison, and psychic damage. On a successful save, a creature takes half as much damage only.

^Tags: #monster #type_unknown