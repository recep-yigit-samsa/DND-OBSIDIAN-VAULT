# Fire Kraken

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Fire Kraken | Elemental | 21 | 402 (23d20 + 161) | 16 | walk: 30 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d6 + 8 + 2d6 + 12d6 | 23 | - |
| Tentacle | 2d4 + 8 + 2d4 | 16 | - |
| Fling | 1d6 | 16 | - |


**Multiattack.** The kraken makes two attacks using its Tentacle, Fling, or a combination of the two.

**Bite.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}18 ({@damage 3d6 + 8}) piercing damage and 7 ({@damage 2d6}) fire damage. If the target is a Large or smaller creature {@condition grappled} by the kraken, the creature is swallowed and the grapple ends. While swallowed, a creature has the {@condition blinded} and {@condition restrained} conditions, has {@quickref Cover||3||total cover} against attacks and other effects outside the kraken, and takes 42 ({@damage 12d6}) fire damage at the start of the kraken's turns. If the kraken takes 50 damage or more on a single turn from a creature inside it, it must succeed on a {@dc 23} Constitution saving throw or regurgitate all swallowed creatures, which fall into a space within 10 feet of the kraken and now have the {@condition prone} condition. If the kraken dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 15 feet of movement, exiting with the {@condition prone} condition.

**Tentacle.** {@atk mw} {@hit 15} to hit, reach 20 ft., one target. {@h}13 ({@damage 2d4 + 8}) fire damage. If the target is a Huge or smaller creature, it has the {@condition grappled} condition (escape {@dc 16}). While {@condition grappled}, the target also has the {@condition restrained} condition. Any target that starts its turn {@condition grappled} by the kraken takes 5 ({@damage 2d4}) fire damage. The kraken has five tentacles, each of which can grapple one target.

**Fling.** One Large or smaller object or creature {@condition grappled} by the kraken is thrown up to 60 feet in a random direction, and now has the {@condition prone} condition. If a thrown target strikes a solid surface, the target takes 3 ({@damage 1d6}) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at a creature, that creature must succeed on a {@dc 16} Dexterity saving throw or take the same damage and be knocked down with the {@condition prone} condition.

^Tags: #monster #type_elemental