# Queen of Night and Magic

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Queen of Night and Magic | Fey | 21 | 225 (30d8 + 90) | 22 | walk: 30 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rapier | 1d8 + 4 + 4d6 | - | - |
| Star Strike | 2d8 + 8 + 2d8 | - | - |
| Unravel | - | - | - |
| Shadow Rift {@recharge 5} | 8d8 + 8d8 | 23 | - |


**Multiattack.** The Queen of Night and Magic makes three Rapier or Star Strike attacks. She can replace one attack with a use of Spellcasting or Unravel.

**Rapier.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d8 + 4}) piercing damage plus 14 ({@damage 4d6}) cold damage.

**Star Strike.** {@atk rs} {@hit 15} to hit, range 120 ft., one target. {@h}17 ({@damage 2d8 + 8}) fire damage plus 9 ({@damage 2d8}) radiant damage.

**Unravel.** The Queen of Night and Magic ends one magical effect she can see within 60 feet of her. To do so, she must succeed on a Charisma check against a DC of 10 + the spell's level or the magical effect's DC, whichever is higher.

**Shadow Rift {@recharge 5}.** The Queen of Night and Magic creates a shadowy rift on a point she can see within 120 feet. Each creature within the 20 feet of the rift must make a {@dc 23} Constitution saving throw. On a failure, a creature takes 36 ({@damage 8d8}) cold damage and 36 ({@damage 8d8}) necrotic damage and is {@condition restrained} by wisps of icy shadow for 1 minute. On a success, a creature takes half the damage and isn't {@condition restrained}. A {@condition restrained} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_fey