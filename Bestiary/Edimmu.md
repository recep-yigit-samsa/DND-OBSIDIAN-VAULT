# Edimmu

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Edimmu | Undead | 4 | 75 (10d8 + 30) | 15 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 14 | - |
| Draining Touch | 2d8 + 4 | 14 | - |


**Multiattack.** The edimmu makes two Draining Touch attacks. If both attacks hit one creature that isn't a Construct or Undead, the target must succeed on a {@dc 14} Constitution saving throw or suffer one level of {@condition exhaustion}. A creature that fails this saving throw by 5 or more is also {@condition stunned} until the end of its next turn.

**Draining Touch.** {@atk ms} {@hit 6} to hit, reach 5 ft., one creature. {@h}13 ({@damage 2d8 + 4}) necrotic damage, and the target must succeed on a {@dc 14} Constitution saving throw or its hp maximum is reduced by an amount equal to the damage taken. This reduction lasts until the creature finishes a long rest after drinking 1 pint of water. The target dies if this effect reduces its hp maximum to 0.

^Tags: #monster #type_undead