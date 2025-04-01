# Dau

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dau | Fey | 4 | 49 (9d6 + 18) | 13 | walk: 20 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 1d6 + 3 + 3d6 | 13 | - |


**Multiattack.** The dau makes two Slam attacks.

**Slam.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}6 ({@damage 1d6 + 3}) bludgeoning damage plus 10 ({@damage 3d6}) necrotic damage, and the dau regains hp equal to the necrotic damage dealt. The target must succeed on a {@dc 13} Constitution saving throw or its hp maximum is reduced by an amount equal to the necrotic damage dealt. This reduction lasts until the creature finishes a long rest. The creature dies if this effect reduces its hp maximum to 0.

^Tags: #monster #type_fey