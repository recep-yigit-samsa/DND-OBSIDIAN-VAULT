# Urochar

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Urochar | Aberration | 17 | 256 (19d12 + 133) | 19 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 4d8 + 7 | 19 | - |
| Paralyzing Gaze | - | 19 | - |
| Strangling Grasp | 8d8 | 19 | - |


**Multiattack.** The urochar can use its Paralyzing Gaze. It then makes four Tentacle attacks.

**Tentacle.** {@atk mw} {@hit 13} to hit, reach 20 ft., one target. {@h}25 ({@damage 4d8 + 7}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 19}) if it is a Large or smaller creature. Until this grapple ends, the target is {@condition restrained}. The urochar has four tentacles, each can grapple only one target.

**Paralyzing Gaze.** The urochar turns its eerie gaze upon one creature it can see within 60 feet of it. The target must succeed on a {@dc 19} Wisdom saving throw or be {@condition paralyzed} for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to the urochar's Paralyzing Gaze for the next 24 hours.

**Strangling Grasp.** Each creature {@condition grappled} by the urochar must make a {@dc 19} Strength saving throw. On a failure, a creature takes 36 ({@damage 8d8}) bludgeoning damage and can't breathe until the grapple ends. On a success, a creature takes half the damage and can still breathe.

^Tags: #monster #type_aberration