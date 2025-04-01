# Gluttony Seraph

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gluttony Seraph | Celestial | 14 | 218 (19d12 + 95) | 15 | walk: 30 ft., fly: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d12 + 5 + 2d8 | 18 | - |
| Claw | 2d6 + 5 + 2d8 | - | - |
| Tongue | 2d4 + 5 + 2d8 | 18 | - |
| Swallow | 4d8 + 2d8 | 20 | - |


**Multiattack.** The seraph makes three attacks, only one of which can be a bite.

**Bite.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}24 ({@damage 3d12 + 5}) piercing damage and 9 ({@damage 2d8}) radiant damage. If the target is a Large or smaller creature, it is {@condition grappled} (escape {@dc 18}). Until this grapple ends, the target is {@condition restrained}, and the seraph can't bite another target.

**Claw.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage and 9 ({@damage 2d8}) radiant damage.

**Tongue.** {@atk mw} {@hit 10} to hit, reach 20 ft., one creature. {@h}10 ({@damage 2d4 + 5}) bludgeoning damage and 9 ({@damage 2d8}) radiant damage, and the target is {@condition grappled} (escape {@dc 18}) and pulled to within 5 feet of the seraph. Until the grapple ends, the target is {@condition restrained}, and the seraph can't use its tongue or bite on another target.

**Swallow.** The seraph makes one bite attack against a Medium or smaller creature it holds {@condition grappled}. If the attack hits, the target takes the bite's damage, the grapple ends, and the target is swallowed. While swallowed, a creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against anything originating outside the seraph, and takes 18 ({@damage 4d8}) acid damage and 9 ({@damage 2d8}) radiant damage at the start of each of the seraph's turns. The seraph can have only one creature swallowed at a time. If the seraph takes 35 damage or more on a single turn from a creature inside it, the seraph must succeed on a {@dc 20} Constitution saving throw at the end of that turn or regurgitate the swallowed creature, which falls {@condition prone} in a space within 10 feet of the seraph. If the seraph dies, the swallowed creature is no longer {@condition restrained} by it and can escape the corpse by using 10 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_celestial