# Scion of Stronmaus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Scion of Stronmaus | Unknown | 27 | 656 (32d20 + 320) | 20 | walk: 60 ft., fly: {'number': 80, 'condition': '(hover)'} ft., swim: 80 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Lightning Sword | 4d12 + 10 + 4d10 | - | - |
| Hailstone | 4d10 + 10 + 4d8 | 26 | - |
| Slam | 4d12 + 10 | - | - |


**Multiattack.** The scion makes one attack using Lightning Sword or Hailstone, as well as two Slam attacks.

**Lightning Sword.** {@atk mw} {@hit 18} to hit, reach 30 ft., one target. {@h}36 ({@damage 4d12 + 10}) force damage plus 22 ({@damage 4d10}) lightning damage.

**Hailstone.** {@atk rw} {@hit 18} to hit, range 120/480 ft., one target. {@h}32 ({@damage 4d10 + 10}) bludgeoning damage plus 18 ({@damage 4d8}) cold damage, and the target must succeed on a {@dc 26} Strength saving throw or have the {@condition prone} condition.

**Slam.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}36 ({@damage 4d12 + 10}) force damage.

^Tags: #monster #type_unknown