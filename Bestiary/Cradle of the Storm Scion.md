# Cradle of the Storm Scion

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cradle of the Storm Scion | Elemental | 27 | 682 (35d20 + 315) | 19 | walk: 40 ft., fly: {'number': 60, 'condition': '(hover)'} ft., swim: 60 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d12 + 10 + 3d12 | - | - |
| Spit Hailstone | 4d10 + 10 + 4d6 | 26 | - |
| Lightning Barrage {@recharge 5} | 11d12 | 22 | - |


**Multiattack.** The cradle makes three Slam or Spit Hailstone attacks in any combination.

**Slam.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}36 ({@damage 4d12 + 10}) bludgeoning damage plus 19 ({@damage 3d12}) lightning damage.

**Spit Hailstone.** {@atk rw} {@hit 18} to hit, range 120 ft., one target. {@h}32 ({@damage 4d10 + 10}) bludgeoning damage plus 14 ({@damage 4d6}) cold damage, and the target must succeed on a {@dc 26} Strength saving throw or have the {@condition prone} condition.

**Lightning Barrage {@recharge 5}.** The cradle hurls multiple magical lightning bolts at up to two creatures it can see within 500 feet of itself. Each target must make a {@dc 22} Dexterity saving throw. On a failed save, the target takes 71 ({@damage 11d12}) lightning damage and has the {@condition stunned} condition until the end of its next turn. On a successful save, the target takes half as much damage only.

^Tags: #monster #type_elemental