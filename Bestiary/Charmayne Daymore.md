# Charmayne Daymore

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Charmayne Daymore | Unknown | 10 | 123 (19d8 + 38) | 12 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Ashen Burst | 5d6 | - | - |
| Cinder Spite {@recharge 5} | 10d6 | 17 | - |


**Multiattack.** Charmayne makes three Ashen Burst attacks. She can replace one of these attacks with one use of Spellcasting.

**Ashen Burst.** {@atk ms,rs} {@hit 9} to hit, reach 5 ft. or range 60 ft., one target. {@h}17 ({@damage 5d6}) fire damage.

**Cinder Spite {@recharge 5}.** Charmayne creates a magical explosion of fire centered on a point she can see within 120 feet of herself. Each creature in a 20-foot-radius sphere centered on that point must make a {@dc 17} Dexterity saving throw, taking 35 ({@damage 10d6}) fire damage on a failed save, or half as much damage on a successful one. A Humanoid reduced to 0 hit points by this damage dies and is transformed into a Tiny charcoal figurine.

^Tags: #monster #type_unknown