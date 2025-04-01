# Lindwurm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lindwurm | Dragon | 6 | 136 (16d10 + 48) | 15 | walk: 40 ft., swim: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 | 15 | - |
| Claw | 2d6 + 5 | - | - |
| Constrict | 2d8 + 5 | 15 | - |


**Multiattack.** The lindwurm makes one Bite attack and two Claw attacks. It can replace its Bite attack with one Constrict attack.

**Bite.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage. If the target is a creature, it must succeed on a {@dc 15} Constitution saving throw or contract a disease and be {@condition poisoned} until the disease is cured. At the end of each long rest, the diseased creature must repeat the saving throw. On a failure, the creature suffers one level of {@condition exhaustion} and doesn't regain expended Hit Dice from the rest. On a success, the creature's {@condition exhaustion} level decreases by one, and it regains expended Hit Dice as normal from the rest. If a successful saving throw reduces the diseased creature's level of {@condition exhaustion} below 1, the creature recovers from the disease, ending it.

**Claw.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage.

**Constrict.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}14 ({@damage 2d8 + 5}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 15}). Until this grapple ends, the target is {@condition restrained}, and the lindwurm can't Constrict another target.

^Tags: #monster #type_dragon