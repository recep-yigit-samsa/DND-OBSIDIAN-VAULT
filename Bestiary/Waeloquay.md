# Waeloquay

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Waeloquay | Elemental | 18 | 290 (20d20 + 80) | 14 | walk: 30 ft., swim: 90 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d8 + 8 | - | - |
| Whelm {@recharge 4} | 3d8 + 8 + 3d8 + 8 | 22 | - |


**Multiattack.** Waeloquay makes three Slam attacks.

**Slam.** {@atk mw} {@hit 14} to hit, reach 15 ft., one target. {@h}26 ({@damage 4d8 + 8}) bludgeoning damage.

**Whelm {@recharge 4}.** Each creature in Waeloquay's space must make a {@dc 22} Strength saving throw. On a failed save, a target takes 21 ({@damage 3d8 + 8}) bludgeoning damage. If it is Large or smaller, it also has the {@condition grappled} condition (escape {@dc 20}). Until this grapple ends, the target is {@condition restrained} and unable to breathe, unless it can breathe water. If the save is successful, the target is pushed out of Waeloquay's space. Waeloquay can grapple one Large creature or up to four Medium or smaller creatures at one time. At the start of each of Waeloquay's turns, each target {@condition grappled} by it takes 21 ({@damage 3d8 + 8}) bludgeoning damage. A creature within 5 feet of Waeloquay can pull a creature or object out of it by taking an action to make a {@dc 22} Strength check and succeeding.

^Tags: #monster #type_elemental