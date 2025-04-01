# Nightgarm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nightgarm | Monstrosity | 6 | 152 (16d10 + 64) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 + 3d6 | 15 | - |
| Claw | 2d6 + 5 | - | - |
| Lupine Howl (1/Day) | - | - | - |


**Multiattack.** The nightgarm makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage. If the target is a Medium or smaller creature, it must succeed on a {@dc 15} Strength saving throw or be swallowed. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the nightgarm, and it takes 10 ({@damage 3d6}) acid damage at the start of each of the nightgarm's turns. The nightgarm can have only one creature swallowed at a time. If the nightgarm takes 20 damage or more on a single turn from the swallowed creature, the nightgarm must succeed on a {@dc 14} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 5 feet of the nightgarm. If the nightgarm dies, a swallowed creature is no longer {@condition restrained} by her and can escape from the corpse by using 10 feet of movement, exiting {@condition prone}.

**Claw.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage.

**Lupine Howl (1/Day).** The nightgarm magically calls {@dice 2d4} wolves or 2 dire wolves. The wolves arrive in {@dice 1d4} rounds, acting as allies of the nightgarm and obeying her telepathic commands. The wolves remain for 1 hour, until the nightgarm dies, or until the nightgarm dismisses them as a bonus action.

^Tags: #monster #type_monstrosity