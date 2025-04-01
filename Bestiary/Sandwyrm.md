# Sandwyrm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sandwyrm | Dragon | 6 | 142 (15d10 + 60) | 15 | walk: 20 ft., burrow: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 5 | - | - |
| Gore | 1d12 + 5 | - | - |
| Stinger | 1d4 + 5 + 4d6 | 15 | - |


**Multiattack.** The sandwyrm makes one Bite attack, one Gore attack, and one Stinger attack.

**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one creature. {@h}12 ({@damage 2d6 + 5}) piercing damage.

**Gore.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}11 ({@damage 1d12 + 5}) piercing damage.

**Stinger.** {@atk mw} {@hit 8} to hit, reach 10 ft., one creature. {@h}9 ({@damage 1d4 + 5}) piercing damage, and the target must make a {@dc 15} Constitution saving throw, taking 14 ({@damage 4d6}) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hp, the target is stable but {@condition poisoned} for 1 hour, even after regaining hp, and is {@condition paralyzed} while {@condition poisoned} in this way.

^Tags: #monster #type_dragon