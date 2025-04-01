# Caprathorn

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Caprathorn | Fiend | 21 | 250 (20d12 + 120) | 19 | walk: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Gore | 4d8 + 7 | - | - |
| Stomp | 4d8 + 7 | - | - |
| Thorns | 4d6 + 7 | - | - |


**Multiattack.** The caprathorn makes three attacks, one with its gore, one with its stomp, and one with its thorns.

**Gore.** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}25 ({@damage 4d8 + 7}) bludgeoning damage.

**Stomp.** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}25 ({@damage 4d8 + 7}) bludgeoning damage.

**Thorns.** {@atk mw,rw} {@hit 14} to hit, reach 10 ft. or range 30/120 ft., one target. {@h}21 ({@damage 4d6 + 7}) piercing damage. Being within 5 feet of a hostile creature doesn't cause the caprathorn to have disadvantage on the ranged attack roll.

^Tags: #monster #type_fiend