# Oshundo the Alhoon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Oshundo the Alhoon | Unknown | 10 | 150 (20d8 + 60) | 15 | walk: 30 ft., fly: {'number': 15, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Chilling Grasp | 4d6 | - | - |
| Arcane Bolt | 8d6 | - | - |
| Thundering Blast {@recharge 5} | 4d8 + 4 | 16 | - |


**Multiattack.** Oshundo makes two Chilling Grasp or Arcane Bolt attacks.

**Chilling Grasp.** {@atk ms} {@hit 8} to hit, reach 5 ft., one target. {@h}14 ({@damage 4d6}) cold damage, and Oshundo regains 14 hit points if the target is a creature.

**Arcane Bolt.** {@atk rs} {@hit 8} to hit, range 120 ft., one target. {@h}28 ({@damage 8d6}) force damage.

**Thundering Blast {@recharge 5}.** Oshundo emits a wave of domineering energy in a 60-foot cone. Each creature in that area must succeed on a {@dc 16} Intelligence saving throw or take 22 ({@damage 4d8 + 4}) thunder damage and have the {@condition stunned} condition for 1 minute. A {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown