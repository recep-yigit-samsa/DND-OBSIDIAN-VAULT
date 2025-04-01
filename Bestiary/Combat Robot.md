# Combat Robot

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Combat Robot | Construct | 6 | 112 (15d8 + 45) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 1d10 + 5 | 16 | - |
| Laser Beam | 4d6 + 2 | - | - |
| Grenade Launcher {@recharge 5} | - | - | - |
| Concussion Grenade | 6d6 | 15 | - |
| Sleep Grenade | - | 15 | - |


**Multiattack.** The robot makes two Tentacle attacks or three Laser Beam attacks.

**Tentacle.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}10 ({@damage 1d10 + 5}) bludgeoning damage. If the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 16}). While {@condition grappled}, the target also has the {@condition restrained} condition. The robot has two tentacles, each of which can grapple one target.

**Laser Beam.** {@atk rw} {@hit 5} to hit, range 120 ft., one target. {@h}16 ({@damage 4d6 + 2}) radiant damage.

**Grenade Launcher {@recharge 5}.** The robot fires a grenade at a point it can see within 120 feet of itself. The grenade explodes in a 20-foot-radius sphere centered on that point, creating one of the following effects (robot's choice):

**Concussion Grenade.** Each creature in the sphere must make a {@dc 15} Dexterity saving throw, taking 21 ({@damage 6d6}) force damage on a failed save or half as much damage on a successful one.

**Sleep Grenade.** Each creature in the sphere must succeed on a {@dc 15} Constitution saving throw or have the {@condition unconscious} condition for 1 hour. The condition ends on a creature early if the creature takes damage or if another creature uses an action to shake it awake.

^Tags: #monster #type_construct