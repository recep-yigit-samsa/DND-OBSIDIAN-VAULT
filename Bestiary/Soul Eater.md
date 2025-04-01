# Soul Eater

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Soul Eater | Fiend | 7 | 105 (14d8 + 42) | 16 | walk: 30 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d6 + 6 + 3d6 | - | - |
| Hasten Consumption {@recharge 5} | 9d6 | 14 | - |


**Multiattack.** The soul eater makes two Claw attacks.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage plus 10 ({@damage 3d6}) psychic damage.

**Hasten Consumption {@recharge 5}.** The soul eater emits a wave of psychic energy to hasten the demise of nearby creatures, bringing them one step closer to having their souls consumed. Each creature within 20 feet of the soul eater must make a {@dc 14} Charisma saving throw, taking 31 ({@damage 9d6}) psychic damage on a failed save, or half as much damage on a successful one. A creature reduced to below half its hp maximum by this effect has disadvantage on the saving throw against the soul eater's Soul Drain for 1 minute.

^Tags: #monster #type_fiend