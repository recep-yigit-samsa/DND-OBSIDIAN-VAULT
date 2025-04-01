# Hertilod

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hertilod | Monstrosity | 17 | 241 (21d12 + 105) | 14 | walk: 50 ft., climb: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 6 + 2d12 + 2d12 | 20 | - |
| Claw | 2d10 + 6 | - | - |


**Multiattack.** The hertilod makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d8 + 6}) piercing damage plus 13 ({@damage 2d12}) poison damage. If the target is a Large or smaller creature, it must succeed on a {@dc 20} Strength saving throw or be swallowed by the hertilod. A swallowed creature has the {@condition blinded} and {@condition restrained} conditions, and it has {@quickref Cover||3||total cover} against attacks and other effects outside the hertilod. At the start of each of the hertilod's turns, each swallowed creature takes 13 ({@damage 2d12}) poison damage from the poisonous secretion in the hertilod's gullet. The hertilod's gullet can hold up to two creatures at a time. If the hertilod takes 40 damage or more on a single turn from a swallowed creature, the hertilod must succeed on a {@dc 15} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which lands in a space within 10 feet of the hertilod and has the {@condition prone} condition. If the hertilod dies, a swallowed creature is no longer {@condition restrained} and can escape from the corpse by using 10 feet of movement, exiting with the {@condition prone} condition.

**Claw.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}17 ({@damage 2d10 + 6}) slashing damage.

^Tags: #monster #type_monstrosity