# Kobold Alchemist

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Kobold Alchemist | Unknown | 2 | 44 (8d6 + 16) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Alchemical Dagger | 1d4 + 3 piercing | - | - |
| Alchemical Bolt | 2d6 + 3 | - | - |
| Alchemical Vapors {@recharge} | 5d6 | 13 | - |
| Explosive Flask {@recharge 5} | 4d6 | 13 | - |


**Multiattack.** The kobold makes two Alchemical Dagger or Alchemical Bolt attacks.

**Alchemical Dagger.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}5 {@damage 1d4 + 3} piercing damage plus 3 ({@damage 1d6}) damage of the type determined by Apothecary.

**Alchemical Bolt.** {@atk rs} {@hit 5} to hit, range 60 ft., one target. {@h}10 ({@damage 2d6 + 3}) damage of the type determined by Apothecary.

**Alchemical Vapors {@recharge}.** The kobold alchemist releases alchemical vapors pleasing to draconic senses and unpleasant to all others. Each creature that isn't a dragonborn or kobold within 15 feet of the alchemist must make a {@dc 13} Constitution saving throw, taking 17 ({@damage 5d6}) poison damage on a failed save, or half as much damage on a successful one. Each dragonborn and kobold within 15 feet of the alchemist has resistance to damage of the type determined by Apothecary for 1 minute.

**Explosive Flask {@recharge 5}.** The kobold alchemist throws a flask of volatile substances at a point it can see within 30 feet of it. The flask explodes, and each creature within 15 feet of that point must make a {@dc 13} Dexterity saving throw. On a failure, a creature takes 14 {@damage 4d6} damage of the type determined by Apothecary and is {@condition poisoned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition poisoned}. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown