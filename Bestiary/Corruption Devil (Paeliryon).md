# Corruption Devil (Paeliryon)

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Corruption Devil (Paeliryon) | Unknown | 14 | 218 (19d10 + 114) | 16 | walk: 20 ft., burrow: 20 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d10 + 5 + 3d6 | - | - |
| Draining Grasp {@recharge 4} | - | - | - |


**Multiattack.** The paeliryon makes three Claw attacks. It can replace one of the attacks with Draining Grasp (if available).

**Claw.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) slashing damage plus 10 ({@damage 3d6}) fire damage.

**Draining Grasp {@recharge 4}.** The paeliryon makes a Claw attack. On a hit, the target's Charisma score is reduced by 2 ({@dice 1d4}). This reduction lasts until the target finishes a short or long rest. A creature whose Charisma is reduced to 3 or less because of this ability, has the {@condition stunned} condition for 1 minute.

^Tags: #monster #type_unknown