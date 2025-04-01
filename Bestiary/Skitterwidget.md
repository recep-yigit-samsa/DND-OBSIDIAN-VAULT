# Skitterwidget

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Skitterwidget | Construct | 5 | 85 (10d8 + 40) | 18 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 3 | 13 | - |
| Tail | 1d6 + 3 + 3d6 | 15 | - |


**Multiattack.** The skitterwidget makes two attacks: one with its bite and one with its tail.

**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) piercing damage. If the target is a creature, it is {@condition grappled} by the skitterwidget (escape {@dc 13}).

**Tail.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage plus 10 ({@damage 3d6}) lightning damage, and if the target is a creature, it must succeed on a {@dc 15} Constitution saving throw or be {@condition stunned} until the end of its next turn.

^Tags: #monster #type_construct