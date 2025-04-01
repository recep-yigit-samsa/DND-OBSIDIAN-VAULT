# Zombie Clot

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Zombie Clot | Undead | 6 | 104 (11d12 + 33) | 12 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 3d8 + 5 | - | - |
| Flesh Entomb {@recharge 5} | 3d10 + 3d6 | 16 | - |


**Multiattack.** The zombie makes two Slam attacks.

**Slam.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}18 ({@damage 3d8 + 5}) bludgeoning damage.

**Flesh Entomb {@recharge 5}.** The zombie flings a detached clump of corpses at a creature it can see within 30 feet of it. The target must succeed on a {@dc 16} Strength saving throw or take 16 ({@damage 3d10}) bludgeoning damage, and if the target is a Large or smaller creature, it becomes entombed in dead flesh. A creature entombed in the dead flesh is {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects outside the dead flesh, and takes 10 ({@damage 3d6}) necrotic damage at the start of each of its turns. The creature can be freed if the dead flesh is destroyed. The dead flesh is a Large object with AC 10, 25 hit points, and immunity to poison and psychic damage.

^Tags: #monster #type_undead