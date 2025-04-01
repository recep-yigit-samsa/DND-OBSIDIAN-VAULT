# Queen of Witches

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Queen of Witches | Fey | 17 | 218 (23d10 + 92) | 18 | walk: 40 ft., fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 20 | - |
| Moonsilver Ring | 2d8 + 6 + 2d6 | - | - |
| Mystical Blast | 3d6 + 6 | - | - |
| Spray of Moonlight {@recharge 5} | 12d6 | 20 | - |


**Multiattack.** The Queen of Witches makes three Moonsilver Ring attacks or four Mystical Blast attacks. She can replace one attack with a use of spellcasting. If she hits one creature with two Mystical Blast attacks, the target must succeed on a {@dc 20} Strength saving throw or be pushed up to 10 feet away from her.

**Moonsilver Ring.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d8 + 6}) slashing damage plus 7 ({@damage 2d6}) radiant damage.

**Mystical Blast.** {@atk ms,rs} {@hit 12} to hit, reach 5 ft. or range 120 ft., one target. {@h}16 ({@damage 3d6 + 6}) force damage.

**Spray of Moonlight {@recharge 5}.** The Queen of Witches sends moonlight flooding out from her. Each creature within 15 feet of her must make a {@dc 20} Dexterity saving throw, taking 42 ({@damage 12d6}) radiant damage on a failed save, or half as much damage on a successful one. If the Queen is standing in an area of moonlight when she uses this action, each creature in the area has disadvantage on the saving throw. A creature that fails the saving throw by 5 or more is {@condition blinded} until the end of its next turn.

^Tags: #monster #type_fey