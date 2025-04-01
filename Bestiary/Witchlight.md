# Witchlight

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Witchlight | Construct | 1/4 | 20 (8d4) | 12 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Light Blast | 1d6 + 2 | - | - |
| Flash (3/Day) | - | 12 | - |


**Light Blast.** {@atk ms,rs} {@hit 4} to hit, range 30 ft., one target. {@h}5 ({@damage 1d6 + 2}) radiant damage.

**Flash (3/Day).** The witchlight emits a bright burst of light. Each creature within 20 feet of the witchlight must succeed on a {@dc 12} Dexterity saving throw or be {@condition blinded} for 1 minute. A creature can make a {@dc 12} Constitution saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_construct