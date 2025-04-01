# Eidolon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Eidolon | Undead | 12 | 63 (18d8 - 18) | 9 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Divine Dread | - | 15 | - |


**Divine Dread.** Each creature within 60 feet of the eidolon that can see it must succeed on a {@dc 15} Wisdom saving throw or be {@condition frightened} for 1 minute. While {@condition frightened} in this way, the creature must take the Dash action and move away from the eidolon by the safest available route at the start of each of its turns, unless there is nowhere for it to move, in which case the creature also becomes {@condition stunned} until it can move again. A {@condition frightened} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to any eidolon's Divine Dread for the next 24 hours.

^Tags: #monster #type_undead