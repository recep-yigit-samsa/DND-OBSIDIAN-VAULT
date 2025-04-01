# Lindwyrm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lindwyrm | Dragon | 14 | 186 (12d20 + 60) | 16 | walk: 40 ft., burrow: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 6 + 4d8 | 18 | - |
| Claw | 2d8 + 6 | - | - |
| Swallow | 3d10 + 6 + 6d8 | 18 | - |


**Multiattack.** The lindwyrm makes three attacks: one with its bite and two with its claws. The lindwyrm can substitute a swallow attack for one of its claw attacks.

**Bite.** {@atk mw} {@hit 11} to hit, reach 15 ft., one target. {@h}22 ({@damage 3d10 + 6}) piercing damage and the target must make a {@dc 18} Constitution saving throw, taking 18 ({@damage 4d8}) poison damage on a failed save, or half as much damage on a successful one. On a hit, the target is also {@condition grappled} (escape {@dc 18}). Until this grapple ends, the target is {@condition restrained}, and the lindwyrm can't bite another target.

**Claw.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d8 + 6}) slashing damage.

**Swallow.** {@atk mw} {@hit 11} to hit, reach 5 ft., one Huge or smaller creature the lindwyrm is grappling. {@h}22 ({@damage 3d10 + 6}) piercing damage, the target is swallowed, and the grapple ends. The swallowed target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the lindwyrm, and it takes 27 ({@damage 6d8}) acid damage at the start of each of the lindwyrm's turns. The lindwyrm can have only one target swallowed at a time. If the lindwyrm takes 40 damage or more on a single turn from the swallowed creature, the lindwyrm must succeed on a {@dc 18} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 10 feet of the lindwyrm. If the lindwyrm dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 5 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_dragon