# Su-monster

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Su-monster | Monstrosity | 1 | 27 (5d8 + 5) | 12 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d4 + 2 | - | - |
| Claws | 2d4 + 2 + 4d4 + 2 | - | - |
| Psychic Crush {@recharge 5} | 5d6 | 11 | - |


**Multiattack.** The su-monster makes two attacks: one with its bite and one with its claws.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d4 + 2}) piercing damage.

**Claws.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}7 ({@damage 2d4 + 2}) slashing damage, or 12 ({@damage 4d4 + 2}) slashing damage if the su-monster is hanging by its tail and all four of its limbs are free.

**Psychic Crush {@recharge 5}.** The su-monster targets one creature it can see within 30 feet of it. The target must succeed on a {@dc 11} Wisdom saving throw or take 17 ({@damage 5d6}) psychic damage and be {@condition stunned} for 1 minute. The {@condition stunned} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_monstrosity