# Necrohydra

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Necrohydra | Undead | 9 | 207 (18d12 + 90) | 13 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d4 + 5 + 1d8 | - | - |
| Dreadful Dirge | - | 17 | - |
| Necrotic Bile {@recharge} | 6d6 + 4d8 | 17 | - |


**Multiattack.** The necrohydra makes as many Bite attacks as it has heads.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}7 ({@damage 1d4 + 5}) piercing damage plus 4 ({@damage 1d8}) necrotic damage.

**Dreadful Dirge.** The necrohydra's heads emit a cacophonous, moaning wail. Each creature that isn't a Construct or Undead within 30 feet of the necrohydra that can hear the wail must succeed on a {@dc 17} Wisdom saving throw or be {@condition frightened} until the wail ends. The necrohydra must take a bonus action on its subsequent turns to continue wailing. It can stop wailing at any time. The wail ends if the necrohydra is {@condition incapacitated}. A {@condition frightened} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Necrotic Bile {@recharge}.** The necrohydra spews rotten bile soaked in necrotic energy in a 30-foot cone. Each creature in that area must make a {@dc 17} Dexterity saving throw, taking 21 ({@damage 6d6}) poison damage and 18 ({@damage 4d8}) necrotic damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_undead