# Algorith

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Algorith | Construct | 10 | 153 (18d8 + 72) | 18 | walk: 40 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Logic Razor | 3d10 + 5 | - | - |
| Cone of Negation {@recharge 5} | 6d10 | 16 | - |
| Reality Bomb (5/Day) | 5d10 | 16 | - |


**Multiattack.** The algorith makes three Logic Razor attacks, or it makes two Logic Razor attacks and uses Spellcasting.

**Logic Razor.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}21 ({@damage 3d10 + 5}) force damage.

**Cone of Negation {@recharge 5}.** The algorith projects null energy in a 30-foot cone. Each creature in the area must make a {@dc 16} Dexterity saving throw. On a failure, a creature takes 33 ({@damage 6d10}) force damage and any spell of 4th level or lower on the creature ends, as if it had been the target of a {@spell dispel magic} spell. On a success, a creature takes half the damage and spells on it don't end.

**Reality Bomb (5/Day).** The algorith summons and throws a tiny rune of law at a point it can see within 100 feet. The rune explodes on impact. Each creature within 30 feet of where the rune landed must make a {@dc 16} Dexterity saving throw. On a failure, a creature takes 27 ({@damage 5d10}) force damage and is {@condition stunned} until the end of its next turn. On a success, a creature takes half the damage and isn't {@condition stunned}.

^Tags: #monster #type_construct