# Sathaq Worm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sathaq Worm | Elemental | 10 | 149 (13d12 + 65) | 16 | walk: 20 ft., burrow: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d8 + 6 | 17 | - |
| Slam | 3d8 + 6 | - | - |
| Swallow | 3d6 + 3d6 | 15 | - |


**Multiattack.** The sathaq worm makes one Bite attack and two Slam attacks, or it makes three Slam attacks. It can replace its Bite attack with a use of Swallow.

**Bite.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}24 ({@damage 4d8 + 6}) piercing damage, and the target is {@condition grappled} (escape {@dc 17}). Until this grapple ends, the target is {@condition restrained}, and the sathaq worm can't Bite another target.

**Slam.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}19 ({@damage 3d8 + 6}) bludgeoning damage.

**Swallow.** The sathaq worm makes one Bite attack against a Large or smaller creature it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the worm (including the worm's Agonizing Aura), and takes 10 ({@damage 3d6}) piercing damage and 10 ({@damage 3d6}) acid damage at the start of each of the sathaq worm's turns. The sathaq worm can have only one creature swallowed at a time. If the sathaq worm takes 30 damage or more on a single turn from the swallowed creature, the sathaq worm must succeed on a {@dc 15} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 5 feet of the sathaq worm. If the sathaq worm dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 10 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_elemental