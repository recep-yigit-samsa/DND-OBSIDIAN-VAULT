# Slarkrethel

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Slarkrethel | Unknown | 25 | 472 (27d20 + 189) | 18 | walk: 20 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 10 + 12d6 | 25 | - |
| Tentacle | 3d6 + 10 | 18 | - |
| Fling | 1d6 | 18 | - |
| Lightning Storm | 4d10 | 23 | - |


**Multiattack.** Slarkrethel makes three tentacle attacks, each of which it can replace with one use of Fling.

**Bite.** {@atk mw} {@hit 17} to hit, reach 5 ft., one target. {@h}23 ({@damage 3d8 + 10}) piercing damage. If the target is a Large or smaller creature {@condition grappled} by Slarkrethel, that creature is swallowed, and the grapple ends. While swallowed, the creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside Slarkrethel, and it takes 42 ({@damage 12d6}) acid damage at the start of each of Slarkrethel's turns. If Slarkrethel takes 50 damage or more on a single turn from a creature inside it, Slarkrethel must succeed on a {@dc 25} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of Slarkrethel. If Slarkrethel dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 15 feet of movement, exiting {@condition prone}.

**Tentacle.** {@atk mw} {@hit 17} to hit, reach 30 ft., one target. {@h}20 ({@damage 3d6 + 10}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 18}). Until this grapple ends, the target is {@condition restrained}. Slarkrethel has ten tentacles, each of which can grapple one target.

**Fling.** One Large or smaller object held or creature {@condition grappled} by Slarkrethel is thrown up to 60 feet in a random direction and knocked {@condition prone}. If a thrown target strikes a solid surface, the target takes 3 ({@damage 1d6}) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a {@dc 18} Dexterity saving throw or take the same damage and be knocked {@condition prone}.

**Lightning Storm.** Slarkrethel magically creates three bolts of lightning, each of which can strike a target Slarkrethel can see within 120 feet of it. A target must make a {@dc 23} Dexterity saving throw, taking 22 ({@damage 4d10}) lightning damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_unknown