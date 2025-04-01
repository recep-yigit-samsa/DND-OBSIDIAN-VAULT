# Ancient Titan

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Titan | Unknown | 12 | 198 (12d20 + 72) | 15 | walk: 50 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Greatsword | 8d6 + 8 | - | - |
| Word of Pain | 4d8 + 5 | 17 | - |
| Reality-Altering Words | - | 17 | - |
| Stunning Word {@recharge 5} | 10d8 | 17 | - |


**Multiattack.** The ancient titan can use its Reality-Altering Words. It then makes two Greatsword attacks or three Word of Pain attacks.

**Greatsword.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}36 ({@damage 8d6 + 8}) slashing damage.

**Word of Pain.** {@atk rs} {@hit 9} to hit, range 120 ft., one target. {@h}23 ({@damage 4d8 + 5}) force damage, and the target must succeed on a {@dc 17} Constitution saving throw or have disadvantage on attack rolls, ability checks, and saving throws until the end of its next turn as pain courses through its body.

**Reality-Altering Words.** The titan speaks a phrase that temporarily reshapes reality around it, warping the terrain, displacing creatures, and disrupting magic. Each creature within 30 feet of the titan must succeed on a {@dc 17} Dexterity saving throw or be pulled or pushed up to 25 feet toward or away from the titan (the titan's choice) and knocked {@condition prone}. Instead of pushing or pulling a creature that failed the saving throw, the titan can end one magical effect of its choice of 4th level or lower on that creature. The area then becomes difficult terrain until the start of the titan's next turn. Moving through this difficult terrain doesn't cost the titan extra movement.

**Stunning Word {@recharge 5}.** The titan speaks a brief, echoing word of power at up to three creatures it can see within 60 feet of it. Each target must make a {@dc 17} Constitution saving throw. On a failure, a creature takes 45 ({@damage 10d8}) force damage and is {@condition stunned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition stunned}. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown