# Sand Silhouette

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sand Silhouette | Undead | 6 | 105 (14d8 + 42) | 15 | walk: 30 ft., burrow: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 15 | - |
| Slam | 3d6 + 4 + 1d6 | - | - |
| Engulf | 3d6 | 15 | - |
| Haunted Haboob (3/Day) | 1d6 | 15 | - |


**Multiattack.** The sand silhouette makes two Slam attacks. If both attacks hit a Medium or smaller target, the target is {@condition grappled} (escape {@dc 15}), and the silhouette uses its Engulf on the target.

**Slam.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}14 ({@damage 3d6 + 4}) bludgeoning damage plus 3 ({@damage 1d6}) necrotic damage.

**Engulf.** The sand silhouette engulfs a Medium or smaller creature {@condition grappled} by it. The engulfed target is {@condition blinded} and {@condition restrained}, and it must succeed on a {@dc 15} Constitution saving throw at the start of each of the sand silhouette's turns or take 10 ({@damage 3d6}) necrotic damage. If the sand silhouette moves, the engulfed target moves with it. The sand silhouette can have only one creature engulfed at a time.

**Haunted Haboob (3/Day).** The sand silhouette creates a storm of whirling sand and wailing souls around itself. The storm is a 10-foot radius, 30-foot-tall cylinder centered on the silhouette and moves with the silhouette for 1 minute, until it ends the storm as a bonus action, or until its {@status concentration} ends (as if {@status concentration||concentrating} on a spell). The sandstorm's area is lightly obscured, and a creature that starts its turn in the sandstorm's area or enters it for the first time on a turn must succeed on a {@dc 15} Wisdom saving throw or take 3 ({@damage 1d6}) necrotic damage and be {@condition frightened} for 1 minute. An engulfed creature automatically succeeds on this saving throw. A {@condition frightened} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_undead