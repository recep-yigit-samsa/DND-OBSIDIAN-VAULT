# Galvan Magen

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Galvan Magen | Construct | 3 | 68 (8d8 + 32) | 14 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Shocking Touch | 1d6 + 4 | - | - |
| Static Discharge {@recharge 5} | 4d10 | 14 | - |


**Multiattack.** The magen makes two Shocking Touch attacks.

**Shocking Touch.** {@atk ms} {@hit 6} to hit, reach 5 ft., one target (the magen has advantage on the attack roll if the target is wearing armor made of metal). {@h}7 ({@damage 1d6 + 4}) lightning damage.

**Static Discharge {@recharge 5}.** The magen discharges a lightning bolt in a 60-foot line that is 5 feet wide. Each creature in that line must make a {@dc 14} Dexterity saving throw (with disadvantage if the creature is wearing armor made of metal), taking 22 ({@damage 4d10}) lightning damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct