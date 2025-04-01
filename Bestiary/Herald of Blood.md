# Herald of Blood

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Herald of Blood | Fiend | 12 | 184 (16d12 + 80) | 15 | walk: 30 ft., fly: 50 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Herald's Staff | 2d6 + 6 + 3d8 | - | - |
| Grasping Slam | 2d10 + 6 + 2d8 | 17 | - |
| Blood Bolt | 5d8 + 3 | 17 | - |
| Call Blood {@recharge 5} | 10d8 | 17 | - |


**Multiattack.** The herald makes three Herald's Staff or Blood Bolt attacks, or it makes two Herald's Staff attacks and one Grasping Slam attack.

**Herald's Staff.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}13 ({@damage 2d6 + 6}) bludgeoning damage plus 13 ({@damage 3d8}) necrotic damage.

**Grasping Slam.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 17}) if it is a Large or smaller creature. Until this grapple ends, the target is {@condition restrained} and takes 9 ({@damage 2d8}) necrotic damage at the start of each of its turns, and the herald can't use its Grasping Slam on another target.

**Blood Bolt.** {@atk rs} {@hit 7} to hit, range 120 ft., one target. {@h}25 ({@damage 5d8 + 3}) necrotic damage. If the target is a creature with blood, it must succeed on a {@dc 17} Constitution saving throw or be {@condition poisoned} until the end of its next turn.

**Call Blood {@recharge 5}.** Each creature with blood within 10 feet of the herald must make a {@dc 17} Constitution saving throw, taking 45 ({@damage 10d8}) necrotic damage on a failed save, or half as much damage on a successful one. The herald then gains temporary hp equal to the single highest amount of necrotic damage dealt. A creature that fails the saving throw by 5 or more also suffers one level of {@condition exhaustion}.

^Tags: #monster #type_fiend