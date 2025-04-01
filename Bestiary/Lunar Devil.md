# Lunar Devil

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lunar Devil | Unknown | 8 | 94 (9d10 + 45) | 16 | walk: 40 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 5 + 2d8 | - | - |
| Claw | 2d6 + 5 | - | - |
| Tail | 2d8 + 5 | - | - |
| Hurl Moonlight | 3d8 + 4 | 15 | - |


**Multiattack.** The lunar devil makes one Bite attack, one Claw attack, and one Tail attack, or it makes three Hurl Moonlight attacks.

**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d10 + 5}) piercing damage plus 9 ({@damage 2d8}) cold damage.

**Claw.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage.

**Tail.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}14 ({@damage 2d8 + 5}) bludgeoning damage.

**Hurl Moonlight.** {@atk rs} {@hit 7} to hit, range 150 ft., one target. {@h}17 ({@damage 3d8 + 4}) cold damage, and the target must succeed on a {@dc 15} Constitution saving throw or become {@condition blinded} until the end of its next turn.

^Tags: #monster #type_unknown