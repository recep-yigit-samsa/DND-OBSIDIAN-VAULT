# Tromokratis

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tromokratis | Unknown | 26 | 409 (21d20 + 189) | 22 | walk: 30 ft., swim: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pincer | 3d6 + 10 | 26 | - |
| Tail | 3d8 + 10 | - | - |
| Tentacle Grasp | 3d6 + 10 + 6d6 | 26 | - |
| Bite | 3d12 + 10 + 12d6 | 20 | - |


**Multiattack.** Tromokratis makes three attacks: one with its pincer, one with its tail, and one with its tentacle grasp.

**Pincer.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}20 ({@damage 3d6 + 10}) bludgeoning damage, and if the target is a creature, it is {@condition grappled} (escape {@dc 26}). Until the grapple ends, the target is {@condition restrained}, and Tromokratis can't use this attack on anyone else.

**Tail.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}23 ({@damage 3d8 + 10}) bludgeoning damage, and if the target is a creature, it is knocked {@condition prone}.

**Tentacle Grasp.** {@atk mw} {@hit 18} to hit, reach 20 ft., one creature. {@h}20 ({@damage 3d6 + 10}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 26}). If the target doesn't escape by the end of its next turn, Tromokratis throws the target up to 60 feet in a straight line. The target lands {@condition prone} and takes 21 ({@damage 6d6}) bludgeoning damage.

**Bite.** {@atk mw} {@hit 18} to hit, reach 5 ft., one target. {@h}29 ({@damage 3d12 + 10}) piercing damage. If the target is a Large or smaller creature {@condition grappled} by Tromokratis, that creature is swallowed, and the grapple ends. While swallowed, the creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside Tromokratis, and it takes 42 ({@damage 12d6}) acid damage at the start of each of Tromokratis's turns. If Tromokratis takes 50 damage or more on a single turn from a creature inside it, Tromokratis must succeed on a {@dc 20} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of Tromokratis. If Tromokratis dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 15 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_unknown