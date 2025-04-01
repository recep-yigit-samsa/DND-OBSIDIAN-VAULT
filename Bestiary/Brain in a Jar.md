# Brain in a Jar

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Brain in a Jar | Undead | 3 | 55 (10d6 + 20) | 11 | walk: 0 ft., fly: {'number': 10, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Chill Touch (Cantrip) | 3d8 | - | - |
| Mind Blast {@recharge 5} | 3d8 + 4 | 14 | - |


**Chill Touch (Cantrip).** {@atk rs} {@hit 6} to hit, range 120 ft., one creature. {@h}13 ({@damage 3d8}) necrotic damage, and the target can't regain hit points until the start of the brain's next turn. If the target is undead, it also has disadvantage on attack rolls against the brain until the end of the brain's next turn.

**Mind Blast {@recharge 5}.** The brain magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a {@dc 14} Intelligence saving throw or take 17 ({@damage 3d8 + 4}) psychic damage and be {@condition stunned} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_undead