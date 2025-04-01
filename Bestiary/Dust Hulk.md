# Dust Hulk

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dust Hulk | Elemental | 5 | 68 (8d10 + 24) | 16 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d8 + 4 | - | - |
| Stinging Dust | 3d6 | 14 | - |


**Multiattack.** The dust hulk makes three Slam attacks. It can replace one of these attacks with Stinging Dust.

**Slam.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}13 ({@damage 2d8 + 4}) bludgeoning damage.

**Stinging Dust.** One creature of the dust hulk's choice inside its space must make a {@dc 14} Constitution saving throw. On a failed save, the creature takes 10 ({@damage 3d6}) bludgeoning damage and has the {@condition blinded} condition until the end of its next turn. On a successful save, the creature takes half as much damage only.

^Tags: #monster #type_elemental