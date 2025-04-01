# Scion of Grolantor

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Scion of Grolantor | Unknown | 22 | 402 (23d20 + 161) | 18 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Great Tree Club | 4d10 + 8 | 23 | - |
| Slam | 4d8 + 8 | - | - |
| Boulder | 3d12 + 8 | - | - |
| Inhale {@recharge 5} | 7d6 | 23 | - |


**Multiattack.** The scion makes one Great Tree Club attack and two Slam attacks, or it makes three Boulder attacks.

**Great Tree Club.** {@atk mw} {@hit 15} to hit, reach 30 ft., one target. {@h}30 ({@damage 4d10 + 8}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 23} Strength saving throw or be pushed horizontally up to 100 feet straight away from the scion and have the {@condition prone} condition.

**Slam.** {@atk mw} {@hit 15} to hit, reach 20 ft., one target. {@h}26 ({@damage 4d8 + 8}) force damage.

**Boulder.** {@atk rw} {@hit 15} to hit, range 120/480 ft., one target. {@h}27 ({@damage 3d12 + 8}) bludgeoning damage.

**Inhale {@recharge 5}.** The scion inhales a vortex of air in a 120-foot line that is 15 feet wide. Each creature in that area that is Huge or smaller must succeed on a {@dc 23} Strength saving throw or be pulled up to 120 feet straight toward the scion and be swallowed. A swallowed creature has the {@condition restrained} condition, has {@quickref Cover||3||total cover} against attacks and other effects outside the scion, and takes 24 ({@damage 7d6}) force damage at the start of each of the scion's turns. The scion's stomach can hold up to two creatures at a time. If the scion takes 60 damage or more on a single turn from a creature inside it, the scion must succeed on a {@dc 17} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the scion and has the {@condition prone} condition. If the scion dies, any swallowed creature no longer has the {@condition restrained} condition and can escape from the corpse using 15 feet of movement, exiting with the {@condition prone} condition.

^Tags: #monster #type_unknown