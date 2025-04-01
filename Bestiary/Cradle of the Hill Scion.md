# Cradle of the Hill Scion

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cradle of the Hill Scion | Elemental | 22 | 402 (23d20 + 161) | 19 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d12 + 7 | - | - |
| Spit Rock | 4d8 + 7 | 22 | - |
| Grasping Root | 4d10 + 7 | 17 | - |
| Rolling Hills {@recharge} | 9d12 | 22 | - |


**Multiattack.** The cradle makes three Slam or Spit Rock attacks in any combination and one Grasping Root attack.

**Slam.** {@atk mw} {@hit 14} to hit, reach 20 ft., one target. {@h}33 ({@damage 4d12 + 7}) bludgeoning damage.

**Spit Rock.** {@atk rw} {@hit 14} to hit, range 120 ft., one target. {@h}25 ({@damage 4d8 + 7}) bludgeoning damage, and the target must succeed on a {@dc 22} Strength saving throw or have the {@condition prone} condition.

**Grasping Root.** {@atk mw} {@hit 14} to hit, reach 30 ft., one creature not {@condition grappled} by the cradle. {@h}the target has the {@condition grappled} condition (escape {@dc 17}). Until the grapple ends, the target takes 29 ({@damage 4d10 + 7}) bludgeoning damage at the start of each of its turns. The root has AC 19 and can be severed by dealing 15 or more slashing damage to it on one attack. Cutting the root doesn't hurt the cradle but ends the grapple.

**Rolling Hills {@recharge}.** The cradle magically creates a wave of dirt that extends from a point on the ground within 120 feet of itself. The wave is up to 30 feet long, up to 30 feet tall, and up to 30 feet wide. Each creature in the wave must make a {@dc 22} Strength saving throw. On a failed save, a creature takes 58 ({@damage 9d12}) bludgeoning damage, has the {@condition prone} condition, and is buried under dirt. On a successful save, a creature takes half as much damage only. A buried creature has the {@condition restrained} condition, has {@quickref Cover||3||total cover}, and can't breathe. As an action, a creature buried in this way, or another creature within 5 feet of it that isn't buried, can make a {@dc 17} Strength ({@skill Athletics}) check. On a successful check, the buried creature no longer has the {@condition prone} or {@condition restrained} conditions.

^Tags: #monster #type_elemental