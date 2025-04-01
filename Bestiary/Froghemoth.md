# Froghemoth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Froghemoth | Monstrosity | 10 | 184 (16d12 + 80) | 14 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 3d8 + 6 | 16 | - |
| Bite | 3d10 + 6 + 3d6 | 20 | - |
| Tongue | - | 18 | - |


**Multiattack.** The froghemoth makes two attacks with its tentacles. It can also use its tongue or bite.

**Tentacle.** {@atk mw} {@hit 10} to hit, reach 20 ft., one target. {@h}19 ({@damage 3d8 + 6}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 16}) if it is a Huge or smaller creature. Until the grapple ends, the froghemoth can't use this tentacle on another target. The froghemoth has four tentacles.

**Bite.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}22 ({@damage 3d10 + 6}) piercing damage, and the target is swallowed if it is a Medium or smaller creature. A swallowed creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects outside the froghemoth, and takes 10 ({@damage 3d6}) acid damage at the start of each of the froghemoth's turns. The froghemoth's gullet can hold up to two creatures at a time. If the Froghemoth takes 20 damage or more on a single turn from a creature inside it, the Froghemoth must succeed on a {@dc 20} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls {@condition prone} in a space within 10 feet of the froghemoth. If the froghemoth dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 10 feet of movement, exiting {@condition prone}.

**Tongue.** The Froghemoth targets one Medium or smaller creature that it can see within 20 feet of it. The target must make a {@dc 18} Strength saving throw. On a failed save, the target is pulled into an unoccupied space within 5 feet of the froghemoth, and the froghemoth can make a bite attack against it as a bonus action.

^Tags: #monster #type_monstrosity