# Giant Zombie Constrictor Snake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Zombie Constrictor Snake | Undead | 8 | 187 (22d12 + 44) | 15 | walk: 30 ft., climb: 20 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 4 + 5d6 | 15 | - |
| Constrict | 3d8 + 4 | 16 | - |


**Multiattack.** The snake makes two attacks: one with its bite and one with a constrict attack.

**Bite.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}17 ({@damage 3d8 + 4}) piercing damage, and the target must make a {@dc 15} Constitution saving throw, taking 17 ({@damage 5d6}) poison damage on a failed save, or half as much damage on a successful one.

**Constrict.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}17 ({@damage 3d8 + 4}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 16}). Until this grapple ends, the creature is {@condition restrained} and the snake cannot constrict another target.

^Tags: #monster #type_undead