# Aberrant Spirit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Aberrant Spirit | Aberration | N/A | 40 + 10 for each spell level above 4 |  | walk: 30 ft., fly: {'number': 30, 'condition': '(hover; Beholderkin only)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw (Slaad Only) | 1d10 + 3 + summonSpellLevel Slashing | - | - |
| Eye Ray (Beholderkin Only) | 1d8 + 3 + summonSpellLevel Psychic | - | - |
| Psychic Slam (Mind Flayer Only) | 1d8 + 3 + summonSpellLevel Psychic | - | - |


**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (round down).

**Claw (Slaad Only).** {@atkr m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 5 ft. {@h}{@damage 1d10 + 3 + summonSpellLevel} Slashing damage, and the target can't regain Hit Points until the start of the spirit's next turn.

**Eye Ray (Beholderkin Only).** {@atkr r} {@hitYourSpellAttack Bonus equals your spell attack modifier}, range 150 ft. {@h}{@damage 1d8 + 3 + summonSpellLevel} Psychic damage.

**Psychic Slam (Mind Flayer Only).** {@atkr m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 5 ft. {@h}{@damage 1d8 + 3 + summonSpellLevel} Psychic damage.

^Tags: #monster #type_aberration