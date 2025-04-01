# Air Elemental Myrmidon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Air Elemental Myrmidon | Elemental | 7 | 117 (18d8 + 36) | 18 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Flail | 1d8 + 4 | - | - |
| Lightning Strike {@recharge} | 4d8 | 13 | - |


**Multiattack.** The myrmidon makes three flail attacks.

**Flail.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d8 + 4}) bludgeoning damage.

**Lightning Strike {@recharge}.** The myrmidon makes one flail attack. On a hit, the target takes an extra 18 ({@damage 4d8}) lightning damage, and the target must succeed on a {@dc 13} Constitution saving throw or be {@condition stunned} until the end of the myrmidon's next turn.

^Tags: #monster #type_elemental