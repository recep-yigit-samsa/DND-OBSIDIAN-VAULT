# Refraction of Ilvaash

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Refraction of Ilvaash | Unknown | 15 | 199 (21d12 + 63) | 11 | walk: 10 ft., fly: {'number': 30, 'condition': '(hover)'} ft., swim: 10 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Dissonant Claw | 3d12 + 6 | - | - |
| Mind Blast {@recharge 5} | 5d10 + 6 | 19 | - |
| Teleport | - | - | - |


**Multiattack.** The refraction makes two Dissonant Claw attacks.

**Dissonant Claw.** {@atk mw} {@hit 11} to hit, reach 10 ft. or range 120 ft., one creature. {@h}25 ({@damage 3d12 + 6}) psychic damage. If the target is a creature {@status concentration||concentrating} on a spell, its {@status concentration} is broken.

**Mind Blast {@recharge 5}.** Creatures of the refraction's choice within 60 feet of it must succeed on a {@dc 19} Intelligence saving throw or take 33 ({@damage 5d10 + 6}) psychic damage and have the {@condition stunned} condition for 1 minute. A {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Teleport.** The refraction teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied place that it can see.

^Tags: #monster #type_unknown