# Adult Time Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Time Dragon | Dragon | {'cr': '18', 'lair': '19'} | 250 (20d12 + 120) | 19 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d6 + 7 + 2d6 | - | - |
| Time Breath {@recharge 5} | 8d8 | 20 | - |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}14 ({@damage 2d6 + 7}) slashing damage plus 7 ({@damage 2d6}) force damage.

**Time Breath {@recharge 5}.** The dragon exhales a wave of shimmering light in a 60-foot cone. Nonmagical objects and vegetation in that area that aren't being worn or carried crumble to dust. Each creature in that area must make a {@dc 20} Constitution saving throw. On a failed save, a creature takes 36 ({@damage 8d8}) force damage and is magically weakened as it is desynchronized from the time stream. While the creature is in this state, attack rolls against it have advantage, and it has the {@condition poisoned} condition. On a successful save, a creature takes half as much damage only. A weakened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself after it succeeds on three of these saves.

^Tags: #monster #type_dragon