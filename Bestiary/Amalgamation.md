# Amalgamation

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Amalgamation | Aberration | 23 | 525 (30d20 + 210) | 18 | walk: 5 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 10 + 12d6 | 25 | - |
| Tentacle | 3d6 + 10 | 18 | - |
| Fling | 1d6 | 18 | - |
| Mind-breaking Whispers | 10d6 | 20 | - |
| Contaminating Presence | 3d6 | 20 | - |


**Multiattack.** The amalgamation uses its Contaminating Presence. It then makes three tentacle attacks, each of which it can replace with one use of Fling.

**Bite.** {@atk mw} {@hit 17} to hit, reach 5 ft., one target. {@h}23 ({@damage 3d8 + 10}) piercing damage. If the target is a Large or smaller creature {@condition grappled} by the amalgamation, that creature is swallowed, and the grapple ends. While swallowed, the creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the amalgamation, and it takes 42 ({@damage 12d6}) acid damage and gains one {@adventure level of contamination|DoDk|12} at the start of each of the amalgamation's turns. If the amalgamation takes 50 damage or more on a single turn from a creature inside it, the amalgamation must succeed on a {@dc 25} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the amalgamation. If the amalgamation dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 15 feet of movement, exiting {@condition prone}.

**Tentacle.** {@atk mw} {@hit 17} to hit, reach 50 ft., one target. {@h}20 ({@damage 3d6 + 10}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 18}). Until this grapple ends, the target is {@condition restrained}. The amalgamation has twelve tentacles, each of which can grapple one target.

**Fling.** One Large or smaller object held or creature {@condition grappled} by the amalgamation is thrown up to 60 feet in a direction of the amalgamation's choice and knocked {@condition prone}. If a thrown target strikes a solid surface, the target takes 3 ({@damage 1d6}) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a {@dc 18} Dexterity saving throw or take the same damage and be knocked {@condition prone}.

**Mind-breaking Whispers.** The amalgamation utters a terrible truth within the mind of one creature within 120 feet of it. That creature must succeed on a {@dc 20} Intelligence saving throw. On a failure, it takes 35 ({@damage 10d6}) psychic damage and becomes insane until it finishes a long rest. While insane, it can't take actions, can't understand what other creatures say, can't read, and can speak only in gibberish. A {@spell greater restoration} spell cast on the creature ends this effect.

**Contaminating Presence.** Humanoid creatures within 120 feet of the amalgamation must succeed on a {@dc 20} Constitution saving throw or take 10 ({@damage 3d6}) necrotic damage and gain one {@adventure level of contamination|DoDk|12}.

^Tags: #monster #type_aberration