# Slow Storm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Slow Storm | Elemental | 15 | 220 (21d8 + 126) | 19 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | 1d8 | 18 | - |
| Slam | 3d10 + 5 + 2d8 | - | - |
| Lightning Bolt | 4d8 + 4 | - | - |
| Static Shock {@recharge 5} | 12d8 | 18 | - |


**Multiattack.** The slow storm makes three Slam attacks or four Lightning Bolt attacks. If two Slam attacks hit one creature, the target must succeed on a {@dc 18} Constitution saving throw or be wracked with pain for 1 minute. While the target is wracked with pain, minute bits of electricity dance within its body, and the target takes 4 ({@damage 1d8}) lightning damage for every 5 feet it moves. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Slam.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}21 ({@damage 3d10 + 5}) bludgeoning damage plus 9 ({@damage 2d8}) lightning damage.

**Lightning Bolt.** {@atk rs} {@hit 9} to hit, range 120 ft., one target. {@h}22 ({@damage 4d8 + 4}) lightning damage.

**Static Shock {@recharge 5}.** The slow storm releases built-up electricity in a 60-foot cone. Each creature in the area must make a {@dc 18} Constitution saving throw, taking 54 ({@damage 12d8}) lightning damage on a failed save, or half as much damage on a successful one. A creature that fails this saving throw by 5 or more is also {@condition stunned} for 1 minute. A {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_elemental