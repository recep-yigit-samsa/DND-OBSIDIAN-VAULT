# Drakon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Drakon | Dragon | 5 | 105 (14d10 + 28) | 16 | walk: 30 ft., fly: 60 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 4 + 4d4 | - | - |
| Tail | 1d8 + 4 | - | - |
| Acid Breath {@recharge 5} | 8d6 | 13 | - |


**Multiattack.** The drakon makes one Bite attack and one Tail attack.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage plus 10 ({@damage 4d4}) acid damage.

**Tail.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}8 ({@damage 1d8 + 4}) bludgeoning damage.

**Acid Breath {@recharge 5}.** The drakon exhales acidic vapors in a 15-foot cone. Each creature in that area must make a {@dc 13} Constitution saving throw, taking 28 ({@damage 8d6}) acid damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon