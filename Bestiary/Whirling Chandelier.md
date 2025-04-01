# Whirling Chandelier

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Whirling Chandelier | Construct | 7 | 105 (14d10 + 28) | 13 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Chain | 2d8 + 4 | 15 | - |
| Lamp | 2d4 + 4 + 3d8 | - | - |
| Blazing Vortex {@recharge 5} | 8d8 | 14 | - |


**Multiattack.** The chandelier makes three Chain attacks, three Lamp attacks, or a combination thereof.

**Chain.** {@atk mw} {@hit 7} to hit, reach 15 ft., one target. {@h}13 ({@damage 2d8 + 4}) bludgeoning damage, and the target must succeed on a {@dc 15} Strength saving throw or be pulled into an unoccupied space within 5 feet of the chandelier.

**Lamp.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d4 + 4}) bludgeoning damage plus 13 ({@damage 3d8}) fire damage.

**Blazing Vortex {@recharge 5}.** Each creature within 20 feet of the chandelier and not behind {@quickref Cover||3||total cover} must succeed on a {@dc 14} Constitution saving throw or take 36 ({@damage 8d8}) fire damage and have the {@condition blinded} condition until the start of the chandelier's next turn.

^Tags: #monster #type_construct