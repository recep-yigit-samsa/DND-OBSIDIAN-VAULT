# Dragonborn of Sardior

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dragonborn of Sardior | Humanoid | 6 | 75 (10d8 + 30) | 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Mind Blade | 1d4 + 4 + 3d6 | - | - |
| Heat Breath {@recharge} | 6d8 + 2d8 | 14 | - |


**Multiattack.** The dragonborn makes three Mind Blade attacks.

**Mind Blade.** {@atk mw,rw} {@hit 7} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}6 ({@damage 1d4 + 4}) piercing damage plus 10 ({@damage 3d6}) psychic damage.

**Heat Breath {@recharge}.** The dragonborn exhales a wave of intense heat in a 30-foot cone. Each creature in that area must make a {@dc 14} Constitution saving throw, taking 27 ({@damage 6d8}) fire damage on a failed save, or half as much damage on a successful one. Metal objects in that area glow red-hot until the end of the dragonborn's next turn. Any creature in physical contact with a heated object at the start of its turn must make a {@dc 14} Constitution saving throw. On a failed save, the creature takes 9 ({@damage 2d8}) fire damage and has disadvantage on attack rolls until the start of its next turn.

^Tags: #monster #type_humanoid