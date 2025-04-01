# Faerie Pathlighter

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Faerie Pathlighter | Fey | 2 | 38 (7d8 + 7) | 12 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Shining Strike | 2d6 | 14 | - |


**Multiattack.** The faerie makes two Shining Strike attacks.

**Shining Strike.** {@atk ms,rs} {@hit 6} to hit, reach 5 ft. or range 30 ft., one target. {@h}7 ({@damage 2d6}) radiant damage, and if the target is a creature, it must succeed on a {@dc 14} Dexterity saving throw or be wreathed in light until the end of the faerie's next turn. While a creature is wreathed in light, attack rolls against the creature have advantage, and the creature can't benefit from the {@condition invisible} condition.

^Tags: #monster #type_fey