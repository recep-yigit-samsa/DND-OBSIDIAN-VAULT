# Yeth Hound

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Yeth Hound | Fey | 4 | 51 (6d10 + 18) | 14 | walk: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d6 + 4 + 4d6 | - | - |
| Baleful Baying | - | 13 | - |


**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage, plus 14 ({@damage 4d6}) psychic damage if the target is {@condition frightened}.

**Baleful Baying.** The yeth hound bays magically. Every enemy within 300 feet of the hound that can hear it must succeed on a {@dc 13} Wisdom saving throw or be {@condition frightened} until the end of the hound's next turn or until the hound is {@condition incapacitated}. A {@condition frightened} target that starts its turn within 30 feet of the hound must use all its movement on that turn to get as far from the hound as possible, must finish the move before taking an action, and must take the most direct route, even if hazards lie that way. A target that successfully saves is immune to the baying of all yeth hounds for the next 24 hours.

^Tags: #monster #type_fey