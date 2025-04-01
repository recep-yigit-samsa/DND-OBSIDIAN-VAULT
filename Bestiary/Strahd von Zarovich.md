# Strahd von Zarovich

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Strahd von Zarovich | Unknown | 15 | 144 (17d8 + 68) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack (Vampire Form Only) | - | - | - |
| Unarmed Strike (Vampire or Wolf Form Only) | 1d8 + 4 + 4d6 | 18 | - |
| Bite | 1d6 + 4 + 3d6 | - | - |
| Charm | - | 17 | - |
| Children of the Night (1/Day) | - | - | - |


**Multiattack (Vampire Form Only).** Strahd makes two attacks, only one of which can be a bite attack.

**Unarmed Strike (Vampire or Wolf Form Only).** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d8 + 4}) slashing damage, plus 14 ({@damage 4d6}) necrotic damage. If the target is a creature, Strahd can grapple it (escape {@dc 18}) instead of dealing the slashing damage.

**Bite.** {@atk mw} {@hit 9} to hit, reach 5 ft., one willing creature, or a creature that is {@condition grappled} by Strahd, {@condition incapacitated}, or {@condition restrained}. {@h}7 ({@damage 1d6 + 4}) piercing damage plus 10 ({@damage 3d6}) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and Strahd regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A humanoid slain in this way and then buried in the ground rises the following night as a {@creature vampire spawn} under Strahd's control.

**Charm.** Strahd targets one humanoid he can see within 30 feet of him. If the target can see Strahd, the target must succeed on a {@dc 17} Wisdom saving throw against this magic or be {@condition charmed}. The {@condition charmed} target regards Strahd as a trusted friend to be heeded and protected. The target isn't under Strahd's control, but it takes Strahd's requests and actions in the most favorable way and lets Strahd bite it. Each time Strahd or his companions do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until Strahd is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.

**Children of the Night (1/Day).** Strahd magically calls {@dice 2d4} {@creature swarm of bats||swarms of bats} or {@creature swarm of rats||swarms of rats}, provided that the sun isn't up. While outdoors, Strahd can call {@dice 3d6} {@creature wolf||wolves} instead. The called creatures arrive in {@dice 1d4} rounds, acting as allies of Strahd and obeying his spoken commands. The beasts remain for 1 hour, until Strahd dies, or until he dismisses them as a bonus action.

^Tags: #monster #type_unknown