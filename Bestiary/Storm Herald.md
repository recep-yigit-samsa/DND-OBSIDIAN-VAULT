# Storm Herald

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Storm Herald | Aberration | 17 | 287 (23d12 + 138) | 16 | walk: 50 ft., swim: 100 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 3d6 + 8 | - | - |
| Tentacles | 3d8 + 8 + 3d10 | 18 | - |
| Trident | 3d6 + 8 + 3d8 + 8 + 3d8 | - | - |
| Psychic Wave {@recharge} | 3d10 + 7 | 21 | - |


**Multiattack.** The herald makes one Claw attack, one Tentacles attack, and one Trident attack.

**Claw.** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}18 ({@damage 3d6 + 8}) slashing damage.

**Tentacles.** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}21 ({@damage 3d8 + 8}) bludgeoning damage. If the target is a Large or smaller creature, it has the {@condition grappled} condition (escape {@dc 18}). It also has the {@condition restrained} condition and takes 16 ({@damage 3d10}) psychic damage at the start of each of its turns until this grapple ends. The herald can have only one creature {@condition grappled} this way at a time.

**Trident.** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}18 ({@damage 3d6 + 8}) piercing damage or 21 ({@damage 3d8 + 8}) piercing damage if used with two hands, plus 13 ({@damage 3d8}) lightning damage.

**Psychic Wave {@recharge}.** The herald unleashes a blast of psionic energy into the minds of up to three creatures it can see within 90 feet of itself. Each target must make a {@dc 21} Intelligence saving throw. On a failed save, a target takes 23 ({@damage 3d10 + 7}) psychic damage and has the {@condition stunned} condition for 1 minute. On a successful save, a target takes half as much damage only. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature is reduced to 0 hit points by this psychic damage, it dies and its head explodes if it has one.

^Tags: #monster #type_aberration