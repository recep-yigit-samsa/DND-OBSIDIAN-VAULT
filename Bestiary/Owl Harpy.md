# Owl Harpy

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Owl Harpy | Monstrosity | 5 | 112 (15d8 + 45) | 14 | walk: 20 ft., fly: {'number': 80, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d4 + 3 | - | - |
| Talon | 2d6 + 3 | - | - |
| Sleeping Song | - | 15 | - |
| Hovering Darkness (3/Day) | - | - | - |


**Multiattack.** The owl harpy makes two Claw attacks and two Talon attacks.

**Claw.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}8 ({@damage 2d4 + 3}) slashing damage.

**Talon.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) slashing damage.

**Sleeping Song.** The owl harpy sings a magical melody. Every Humanoid and Giant within 300 feet of the harpy that can hear the song must succeed on a {@dc 15} Wisdom saving throw or fall {@condition unconscious} until the song ends. The harpy must take a bonus action on its subsequent turns to continue singing. It can stop singing at any time. The song ends if the harpy is {@condition incapacitated}. An {@condition unconscious} target wakes if it takes damage or if another creature uses an action to wake it. A target that successfully saves is immune to this harpy's song for the next 24 hours.

**Hovering Darkness (3/Day).** While flying, the owl harpy shakes a fine, magical dander from her wings, and a 15-foot radius of magical darkness extends out from her, moves with her, and spreads around corners. The darkness lasts as long as the owl harpy flies and maintains {@status concentration}, up to 10 minutes (as if {@status concentration||concentrating} on a spell). Darkvision can't penetrate this darkness, and no natural light can illuminate it. If any of the darkness overlaps with an area of light created by a spell of 2nd level or lower, the spell creating the light is dispelled.

^Tags: #monster #type_monstrosity