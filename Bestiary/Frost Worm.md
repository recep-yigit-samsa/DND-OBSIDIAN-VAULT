# Frost Worm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Frost Worm | Monstrosity | 17 | 264 (16d20 + 96) | 18 | walk: 40 ft., burrow: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 9 + 3d6 + 3d6 + 3d6 | 20 | - |
| Trill | - | 20 | - |


**Multiattack.** The worm makes two bite attacks, or uses its Trill and makes a bite attack.

**Bite.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}22 ({@damage 3d8 + 9}) piercing damage plus 10 ({@damage 3d6}) cold damage. If the target is a Large or smaller creature, it must succeed on a {@dc 20} Dexterity saving throw or be swallowed by the worm. A swallowed creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects outside the worm, and takes 10 ({@damage 3d6}) acid damage and 10 ({@damage 3d6}) cold damage at the start of each of the worm's turns. If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a {@dc 20} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the worm.

**Trill.** The frost worm emits a haunting cry. Each creature within 60 feet of the worm that can hear it must succeed on a {@dc 20} Wisdom saving throw or be {@condition stunned} for 1 minute. A creature can repeat the saving throw each time it takes damage and at the end of each of its turns, ending the effect on itself on a success. Once a creature successfully saves against this effect, or if this effect ends for it, that creature is immune to the Trill of all frost worms for the next 24 hours. Frost worms are immune to this effect.

^Tags: #monster #type_monstrosity