# Asmodeus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Asmodeus | Unknown | 30 | 725 (50d10 + 450) | 22 | walk: 30 ft., fly: {'number': 120, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Ruby Rod | 2d8 + 12 | - | - |
| Chilling Gaze | 2d10 + 7 | - | - |
| Hellish Smite | 4d6 + 4d6 | 24 | - |
| Infernal Word: Stun {@recharge 4} | 10d8 | 24 | - |
| Hell-Lord's Suggestion {@recharge 5} | 8d10 | 24 | - |
| Fires of the Nine Hells {@recharge 5} | 20d6 | 24 | - |


**Multiattack.** Asmodeus makes four attacks using Ruby Rod, Chilling Gaze, or a combination of the two. He can replace one of the attacks with Hellish Smite.

**Ruby Rod.** {@atk mw} {@hit 21} to hit, reach 5 ft., one target. {@h}21 ({@damage 2d8 + 12}) necrotic damage, which also reduces the target's hit point maximum by the damage taken. This damage can't reduce a target's hit point maximum below 1. Any effect that removes a disease allows a creature's hit point maximum to return to normal.

**Chilling Gaze.** {@atk rs} {@hit 16} to hit, range 60 ft., one target. {@h}18 ({@damage 2d10 + 7}) cold damage, and the target has a-1 penalty to all attack rolls they make until the end of their next turn. This penalty can stack.

**Hellish Smite.** Asmodeus targets a creature he can see within 300 feet of him, calling down a bolt of hellish lightning. The target must make a {@dc 24} Dexterity saving throw, taking 14 ({@damage 4d6}) lightning damage plus 14 ({@damage 4d6}) fire damage on a failed save, or half as much damage on a successful one.

**Infernal Word: Stun {@recharge 4}.** Asmodeus targets a creature he can see within 120 feet of him. The target must make a {@dc 24} Intelligence saving throw, taking 45 ({@damage 10d8}) force damage on a failed save, or half as much damage on a successful one. A creature that failed the save is {@condition stunned} for up to 1 minute. The {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success, but taking the damage again on a failed save.

**Hell-Lord's Suggestion {@recharge 5}.** Asmodeus targets a creature he can see within 120 feet of him. The target must make a {@dc 24} Charisma saving throw, taking 44 ({@damage 8d10}) psychic damage on a failed save, or half as much damage on a successful one. A creature that failed the save has the {@condition charmed} condition for up to 1 minute. While {@condition charmed}, a creature is controlled by Asmodeus, performing only actions that he suggests. A {@condition charmed} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success, but taking the damage again on a failed save.

**Fires of the Nine Hells {@recharge 5}.** Asmodeus chooses a point he can see within 500 feet of him, which explodes into a roaring inferno. All creatures within a 60-foot-radius sphere centered on that point must make a {@dc 24} Dexterity saving throw, taking 70 ({@damage 20d6}) fire damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_unknown