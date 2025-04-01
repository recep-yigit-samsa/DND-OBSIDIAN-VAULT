# Octon Modron

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Octon Modron | Construct | 11 | 187 (22d10 + 66) | 18 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., swim: 30 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 3d6 + 4 + 2d8 | - | - |
| Whirlwind of Tentacles {@recharge 5} | - | 16 | - |


**Multiattack.** The octon makes three Tentacle attacks.

**Tentacle.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}14 ({@damage 3d6 + 4}) bludgeoning damage plus 9 ({@damage 2d8}) lightning damage.

**Whirlwind of Tentacles {@recharge 5}.** The octon rapidly extends and spins its ring of tentacles. Each creature within 20 feet of the octon must succeed on a {@dc 16} Strength saving throw or be pulled up to 10 feet in a straight line toward the octon. Then, the octon makes two Tentacle attacks against each creature within 10 feet of itself.

^Tags: #monster #type_construct