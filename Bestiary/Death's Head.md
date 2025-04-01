# Death's Head

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Death's Head | Undead | 1/2 | 17 (5d4 + 5) | 16 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Gnashing Bite (Gnashing Head Only) | 1d6 + 1 + 2d6 | - | - |
| Mind-Bending Bite (Aberrant Head Only) | 1d6 + 1 + 1d10 | 10 | - |
| Petrifying Bite (Petrifying Head Only) | 1d4 + 1 | 10 | - |


**Gnashing Bite (Gnashing Head Only).** {@atk mw} {@hit 3} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d6 + 1}) piercing damage plus 7 ({@damage 2d6}) necrotic damage.

**Mind-Bending Bite (Aberrant Head Only).** {@atk mw} {@hit 3} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d6 + 1}) piercing damage plus 5 ({@damage 1d10}) necrotic damage, and the target must succeed on a {@dc 10} Intelligence saving throw or it can't take a reaction until the end of its next turn. Moreover, on its next turn, the target must choose whether it gets a move, an action, or a bonus action; it gets only one of the three.

**Petrifying Bite (Petrifying Head Only).** {@atk mw} {@hit 3} to hit, reach 5 ft., one target. {@h}3 ({@damage 1d4 + 1}) piercing damage, and the target must succeed on a {@dc 10} Constitution saving throw or be {@condition restrained} as it begins to turn to stone. The target must repeat the saving throw at the end of its next turn. On a success, the effect ends. On a failure, the target is {@condition petrified} for 10 minutes.

^Tags: #monster #type_undead