# Scion of Surtur

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Scion of Surtur | Unknown | 25 | 546 (28d20 + 252) | 20 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Lava Blade | 4d10 + 10 + 4d8 | - | - |
| Lava Ball | 3d12 + 10 + 3d6 | 26 | - |
| Slam | 4d8 + 10 | - | - |
| Lava Wave {@recharge 5} | 11d10 | 25 | - |


**Multiattack.** The scion makes one attack using Lava Blade or Lava Ball, as well as two Slam attacks.

**Lava Blade.** {@atk mw} {@hit 18} to hit, reach 30 ft., one target. {@h}32 ({@damage 4d10 + 10}) slashing damage plus 18 ({@damage 4d8}) fire damage.

**Lava Ball.** {@atk rw} {@hit 18} to hit, range 120/480 ft., one target. {@h}29 ({@damage 3d12 + 10}) bludgeoning damage plus 10 ({@damage 3d6}) fire damage, and the target must succeed on a {@dc 26} Strength saving throw or have the {@condition prone} condition.

**Slam.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}28 ({@damage 4d8 + 10}) force damage.

**Lava Wave {@recharge 5}.** The scion emits a wave of lava from its blade, hands, or mouth in a 90-foot cone. Each creature in that area must make a {@dc 25} Dexterity saving throw. On a failed save, a creature takes 60 ({@damage 11d10}) fire damage and has the {@condition restrained} condition from being embedded in hardening rock. A creature can make a {@dc 25} Strength ({@skill Athletics}) check as an action, freeing itself or a creature within reach from the rock on a success. The rock has AC 17 and 40 hit points, and it is immune to fire, poison, and psychic damage. On a successful save, a creature takes half as much damage only.

^Tags: #monster #type_unknown