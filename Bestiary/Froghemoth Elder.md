# Froghemoth Elder

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Froghemoth Elder | Monstrosity | 15 | 207 (18d12 + 90) | 14 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 7 + 3d6 | 20 | - |
| Tentacle | 3d8 + 7 | 20 | - |
| Tongue | - | 20 | - |


**Multiattack.** The froghemoth makes one Bite attack and two Tentacle attacks, and it can use Tongue.

**Bite.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}23 ({@damage 3d10 + 7}) piercing damage, and the target is swallowed if it is a Medium or smaller creature. A swallowed creature has the {@condition blinded} and {@condition restrained} conditions, has {@quickref Cover||3||total cover} against attacks and other effects outside the froghemoth, and takes 10 ({@damage 3d6}) acid damage at the start of each of the froghemoth's turns. The froghemoth's gullet can hold up to three creatures at a time. If the froghemoth takes 25 damage or more on a single turn from a creature inside it, the froghemoth must succeed on a {@dc 20} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which lands in a space within 10 feet of the froghemoth and has the {@condition prone} condition. If the froghemoth dies, any swallowed creatures are no longer {@condition restrained} by it and can escape from the corpse using 10 feet of movement, exiting with the {@condition prone} condition.

**Tentacle.** {@atk mw} {@hit 12} to hit, reach 20 ft., one target. {@h}20 ({@damage 3d8 + 7}) bludgeoning damage, and the target has the {@condition grappled} condition (escape {@dc 20}). Until this grapple ends, the froghemoth can't use this tentacle on another target. The froghemoth has four tentacles.

**Tongue.** The froghemoth targets one Large or smaller creature that it can see within 25 feet of it. The target must make a {@dc 20} Strength saving throw. On a failed save, the target is pulled into an unoccupied space within 5 feet of the froghemoth.

^Tags: #monster #type_monstrosity