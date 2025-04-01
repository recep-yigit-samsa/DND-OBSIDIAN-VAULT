# Bakunawa

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bakunawa | Dragon | 12 | 150 (12d20 + 24) | 15 | walk: 20 ft., fly: 60 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 5 + 2d6 + 3d6 | 17 | - |
| Storm Slam | 1d8 + 5 + 1d10 | - | - |


**Multiattack.** The bakunawa makes one Bite attack and one Storm Slam attack.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage plus 7 ({@damage 2d6}) lightning damage. If the target is a Large or smaller creature, it must succeed on a {@dc 17} Strength saving throw or be swallowed by the bakunawa. A swallowed creature is {@condition blinded} and {@condition restrained}, and it has {@quickref Cover||3||total cover} against attacks and other effects outside the bakunawa. At the start of each of the bakunawa's turns, each swallowed creature takes 10 ({@damage 3d6}) lightning damage. The bakunawa's gullet can hold up to two creatures at a time. If the bakunawa takes 30 damage or more on a single turn from a swallowed creature, the bakunawa must succeed on a {@dc 16} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 15 feet of the bakunawa. If the bakunawa dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 15 feet of movement, exiting {@condition prone}.

**Storm Slam.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}9 ({@damage 1d8 + 5}) bludgeoning damage plus 5 ({@damage 1d10}) thunder damage, and the target is pushed up to 10 feet in a horizontal direction away from the bakunawa.

^Tags: #monster #type_dragon