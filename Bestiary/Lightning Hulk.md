# Lightning Hulk

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lightning Hulk | Elemental | 9 | 102 (12d10 + 36) | 15 | walk: 0 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Arc Lightning | 4d8 + 4d8 | 18 | - |


**Arc Lightning.** {@atk mw,rw} {@hit 9} to hit, reach 10 ft. or range 60 ft., one target. {@h}18 ({@damage 4d8}) lightning damage. If the target is a creature, it can't take reactions until the start of its next turn, and lightning jumps from the target to another creature of the lightning hulk's choice that it can see within 30 feet of the target. The second creature must succeed on a {@dc 18} Dexterity saving throw or take 18 ({@damage 4d8}) lightning damage.

^Tags: #monster #type_elemental