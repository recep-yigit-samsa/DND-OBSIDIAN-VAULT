# Ordeal Tree

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ordeal Tree | Plant | 12 | 186 (12d20 + 60) | 17 | walk: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d10 + 7 | - | - |
| Vine | 3d8 + 7 | 17 | - |
| Enervate (2/Day) | 8d10 | 17 | - |


**Multiattack.** The ordeal tree makes two slam attacks and one attack with a vine or enervate.

**Slam.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}29 ({@damage 4d10 + 7}) bludgeoning damage.

**Vine.** {@atk mw} {@hit 11} to hit, reach 20 ft., one target. {@h}20 ({@damage 3d8 + 7}) slashing damage, and the creature is {@condition grappled} (escape {@dc 17}).

**Enervate (2/Day).** A creature bound to the ordeal tree or {@condition grappled} by it must succeed on a {@dc 17} Constitution saving throw or suffer 44 ({@damage 8d10}) necrotic damage. The ordeal tree gains temporary hit points equal to half the damage done.

^Tags: #monster #type_plant