# Neo-Otyugh

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Neo-Otyugh | Aberration | 7 | 150 (12d12 + 72) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 | 17 | - |
| Tentacle | 1d10 + 5 | 16 | - |
| Tentacle Slam | 3d6 + 5 | 16 | - |


**Multiattack.** The neo-otyugh makes three attacks: one with its bite and two with its tentacles.

**Bite.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage. If the target is a creature, it must succeed on a {@dc 17} Constitution saving throw against disease or become {@condition poisoned} until the disease is cured. Every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by 5 ({@dice 1d10}) on a failure. The disease is cured on a success. The target dies if the disease reduces its hit point maximum to 0. This reduction to the target's hit point maximum lasts until the disease is cured.

**Tentacle.** {@atk mw} {@hit 8} to hit, reach 15 ft., one target. {@h}10 ({@damage 1d10 + 5}) bludgeoning damage. If the target is Large or smaller, it is {@condition grappled} (escape {@dc 16}) and {@condition restrained} until the grapple ends. The neo-otyugh has two tentacles, each of which can grapple one target.

**Tentacle Slam.** The neo-otyugh slams creatures {@condition grappled} by it into each other or a solid surface. Each creature must succeed on a {@dc 16} Constitution saving throw or take 15 ({@damage 3d6 + 5}) bludgeoning damage and be {@condition stunned} until the end of the neo-otyugh's next turn. On a successful save, the target takes half the bludgeoning damage and isn't {@condition stunned}.

^Tags: #monster #type_aberration