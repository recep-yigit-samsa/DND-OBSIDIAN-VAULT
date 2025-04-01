# Fensir Skirmisher

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Fensir Skirmisher | Giant | 6 | 94 (9d10 + 45) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Battleaxe | 2d8 + 4 + 2d10 + 4 | - | - |
| Magic Stone | 2d12 + 2 | 13 | - |
| Mud to Stone {@recharge} | 3d8 | 13 | - |


**Multiattack.** The fensir makes three Battleaxe attacks or two Magic Stone attacks.

**Battleaxe.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) slashing damage, or 15 ({@damage 2d10 + 4}) slashing damage if used with two hands.

**Magic Stone.** {@atk rs} {@hit 5} to hit, range 60 ft., one target. {@h}15 ({@damage 2d12 + 2}) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a {@dc 13} Strength saving throw or have the {@condition prone} condition.

**Mud to Stone {@recharge}.** The fensir lobs a magical mass of mud that splashes all creatures in a 30-foot-radius sphere centered on a point the fensir can see within 60 feet of itself. Each non-fensir creature in that area must succeed on a {@dc 13} Dexterity saving throw or take 13 ({@damage 3d8}) bludgeoning damage and have the {@condition restrained} condition as the mud begins to turn to stone. An affected creature must repeat the saving throw at the end of its next turn. On a successful save, the effect ends on the creature. On a failed save, the creature has the {@condition petrified} condition for 24 hours.

^Tags: #monster #type_giant