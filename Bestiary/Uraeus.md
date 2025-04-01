# Uraeus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Uraeus | Celestial | 2 | 40 (9d4 + 18) | 14 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d6 + 2 + 2d8 + 1d6 | 12 | - |
| Spit Fire | 4d6 + 2 | - | - |
| Searing Breath {@recharge 5} | 3d6 | 12 | - |


**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage plus 9 ({@damage 2d8}) poison damage, and the target must succeed on a {@dc 12} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned}, the target takes 3 ({@damage 1d6}) fire damage at the start of each of its turns. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Spit Fire.** {@atk rw} {@hit 4} to hit, range 20/60 ft., one target. {@h}16 ({@damage 4d6 + 2}) fire damage.

**Searing Breath {@recharge 5}.** The uraeus exhales a 15-foot cone of fire. Each creature in the area must make a {@dc 12} Dexterity saving throw, taking 10 ({@damage 3d6}) fire damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_celestial