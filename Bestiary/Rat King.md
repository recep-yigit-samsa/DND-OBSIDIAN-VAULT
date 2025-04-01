# Rat King

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Rat King | Monstrosity | 5 | 76 (9d8 + 36) | 14 | walk: 30 ft., burrow: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 3 + 2d6 | 14 | - |
| Call Rats (1/Day) | - | - | - |


**Multiattack.** The rat king makes two Bite attacks.

**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) piercing damage plus 7 ({@damage 2d6}) poison damage. If the target is a creature, it must succeed on a {@dc 14} Constitution saving throw or suffer one level of {@condition exhaustion} and become infected with a disease. Until the disease is cured, at the end of each long rest, the creature must repeat the saving throw. On a failure, the creature suffers another level of {@condition exhaustion}. The {@condition exhaustion} lasts until the creature finishes a long rest after the disease is cured. A creature that succeeds on two saving throws recovers from the disease.

**Call Rats (1/Day).** The rat king magically calls {@dice 2d4} rats, {@dice 1d4} giant rats, or 1 swarm of rats. The rats arrive in {@dice 1d4} rounds, acting as allies of the rat king and obeying its spoken commands. The rats remain for 1 hour, until the rat king dies, or until the rat king dismisses them as a bonus action.

^Tags: #monster #type_monstrosity