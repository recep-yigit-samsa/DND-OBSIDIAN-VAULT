# Giant Insect

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Insect | Beast | N/A | 30 + 10 for each spell level above 4 |  | walk: 40 ft., climb: 40 ft., fly: {'number': 40, 'condition': '(Wasp only)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Poison Jab | 1d6 + 3 + summonSpellLevel Piercing + 1d4 Poison | - | - |
| Web Bolt (Spider Only) | 1d10 + 3 + summonSpellLevel Bludgeoning | - | - |


**Multiattack.** The insect makes a number of attacks equal to half this spell's level (round down).

**Poison Jab.** {@atkr m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 10 ft. {@h}{@damage 1d6 + 3 + summonSpellLevel} Piercing damage plus {@damage 1d4} Poison damage.

**Web Bolt (Spider Only).** {@atkr r} {@hitYourSpellAttack Bonus equals your spell attack modifier}, range 60 ft. {@h}{@damage 1d10 + 3 + summonSpellLevel} Bludgeoning damage, and the target's Speed is reduced to 0 until the start of the insect's next turn.

^Tags: #monster #type_beast