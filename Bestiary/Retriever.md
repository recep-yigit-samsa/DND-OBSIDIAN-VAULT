# Retriever

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Retriever | Construct | 14 | 210 (20d10 + 100) | 19 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Foreleg | 2d8 + 6 | - | - |
| Force Beam | 5d10 | 16 | - |
| Paralyzing Beam {@recharge 5} | - | 18 | - |


**Multiattack.** The retriever makes two foreleg attacks and uses its force or paralyzing beam once, if available.

**Foreleg.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d8 + 6}) slashing damage.

**Force Beam.** The retriever targets one creature it can see within 60 feet of it. The target must make a {@dc 16} Dexterity saving throw, taking 27 ({@damage 5d10}) force damage on a failed save, or half as much damage on a successful one.

**Paralyzing Beam {@recharge 5}.** The retriever targets one creature it can see within 60 feet of it. The target must succeed on a {@dc 18} Constitution saving throw or be {@condition paralyzed} for 1 minute. The {@condition paralyzed} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If the {@condition paralyzed} creature is Medium or smaller, the retriever can pick it up as part of the retriever's move and walk or climb with it at full speed.

^Tags: #monster #type_construct