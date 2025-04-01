# Animated Staff

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Animated Staff | Construct | N/A | 40 | 17 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Staff of Frost | - | 12 | - |
| Staff | 2d6 | - | - |


**Staff of Frost.** The staff has 10 charges. It can expend 1 or more of its charges to cast one of the following spells (save {@dc 12}): {@spell cone of cold} (5 charges), {@spell fog cloud} (1 charge), {@spell ice storm} (4 charges), or {@spell wall of ice} (4 charges). It regains {@dice 1d6 + 4} expended charges daily at dawn. If the staff expends its last charge, roll a {@dice d20}. On a 1, the staff turns to water and is destroyed.

**Staff.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}7 ({@damage 2d6}) bludgeoning damage plus 1 cold damage.

^Tags: #monster #type_construct