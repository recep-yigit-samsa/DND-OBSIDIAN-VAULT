# Keg Robot

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Keg Robot | Construct | 2 | 39 (6d8 + 12) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Fist | 1d8 + 3 | - | - |
| Acid Squirt | 1d8 + 3 | - | - |
| Beer Shower | - | 13 | - |
| Hot Oil Spray {@recharge 5} | 1d8 + 3 + 1d6 + 1d6 | 13 | - |


**Fist.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) bludgeoning damage.

**Acid Squirt.** {@atk rw} {@hit 5} to hit, range 20/40 ft., one target. {@h}7 ({@damage 1d8 + 3}) acid damage.

**Beer Shower.** The keg robot spews an unnaturally potent beer in a 15-foot cone or in a 30-foot line that is 5 feet wide. Each creature in the area must succeed on a {@dc 13} Constitution saving throw or be {@condition poisoned}. While {@condition poisoned} in this way, a creature has its speed halved by exposure to the potent brew. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Additionally, the beer shower extinguishes any fires or open flames in its area.

**Hot Oil Spray {@recharge 5}.** The keg robot sprays hot oil in a 15-foot cone or in a 30-foot line that is 5 feet wide. Each creature in the area must make a {@dc 13} Dexterity saving throw. On a failed save, a creature takes 7 ({@damage 1d8 + 3}) fire damage and falls {@condition prone}. On a successful save, a creature takes half as much damage and doesn't fall {@condition prone}. Any creature affected by the hot oil spray that takes fire damage before the oil dries (after 1 minute) takes an additional 3 ({@damage 1d6}) fire damage, and the oil burns away. If the oil that remains in the area of the spray is lit, it burns for {@dice 1d4} rounds and deals 3 ({@damage 1d6}) fire damage to any creature that enters the area for the first time on a turn or ends its turn there.

^Tags: #monster #type_construct