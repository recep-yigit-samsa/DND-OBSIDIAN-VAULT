# Elder Tempest

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Elder Tempest | Elemental | 23 | 264 (16d20 + 96) | 19 | walk: 0 ft., fly: {'number': 120, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Thunderous Slam | 4d6 + 9 | - | - |
| Lightning Storm {@recharge} | 6d8 | 20 | - |


**Multiattack.** The tempest makes two attacks with its thunderous slam.

**Thunderous Slam.** {@atk mw} {@hit 16} to hit, reach 20 ft., one target. {@h}23 ({@damage 4d6 + 9}) thunder damage.

**Lightning Storm {@recharge}.** All other creatures within 120 feet of the tempest must each make a {@dc 20} Dexterity saving throw, taking 27 ({@damage 6d8}) lightning damage on a failed save, or half as much damage on a successful one. If a target's saving throw fails by 5 or more, the creature is also {@condition stunned} until the end of its next turn.

^Tags: #monster #type_elemental