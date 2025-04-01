# Thessalkraken

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Thessalkraken | Unknown | 14 | 207 (18d12 + 90) | 16 | walk: 20 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 7 + 1d10 + 6d6 | 23 | - |
| Tentacle | 3d6 + 7 | 16 | - |
| Fling | 1d6 | 16 | - |
| Acid Saliva {@recharge 5} | 4d10 | 18 | - |


**Multiattack.** The thessalkraken makes one bite attack and two tentacle attacks. It can replace each tentacle attack with one use of Fling.

**Bite.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}20 ({@damage 3d8 + 7}) piercing damage plus 5 ({@damage 1d10}) acid damage. If the target is a Medium or smaller creature {@condition grappled} by the thessalkraken, that creature is swallowed, and the grapple ends. While swallowed, the creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the thessalkraken, and it takes 21 ({@damage 6d6}) acid damage at the start of each of the thessalkraken's turns. If the thessalkraken takes 35 damage or more on a single turn from a creature inside it, it must succeed on a {@dc 23} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the thessalkraken. If the thessalkraken dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 10 feet of movement, exiting {@condition prone}.

**Tentacle.** {@atk mw} {@hit 12} to hit, reach 20 ft., one target. {@h}17 ({@damage 3d6 + 7}) slashing damage, and the target is {@condition grappled} (escape {@dc 16}). Until this grapple ends, the target is {@condition restrained}. The thessalkraken has ten tentacles, each of which can grapple one target.

**Fling.** One Medium or smaller object held or creature {@condition grappled} by the thessalkraken is thrown up to 40 feet in a random direction and knocked {@condition prone}. If a thrown target strikes a solid surface, the target takes 3 ({@damage 1d6}) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a {@dc 16} Dexterity saving throw or take the same damage and be knocked {@condition prone}.

**Acid Saliva {@recharge 5}.** The thessalkraken spits a glob of acid at a point it can see within 60 feet of it. Each creature within 10 feet of that point must make a {@dc 18} Dexterity saving throw, taking 22 ({@damage 4d10}) acid damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_unknown