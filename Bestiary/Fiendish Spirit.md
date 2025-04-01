# Fiendish Spirit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Fiendish Spirit | Fiend | N/A | 50 (Demon only) or 40 (Devil only) or 60 (Yugoloth only) + 15 for each spell level above 6 |  | walk: 40 ft., climb: {'number': 40, 'condition': '(Demon only)'} ft., fly: {'number': 60, 'condition': '(Devil only)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite (Demon Only) | 1d12 + 3 + summonSpellLevel Necrotic | - | - |
| Claws (Yugoloth Only) | 1d8 + 3 + summonSpellLevel Slashing | - | - |
| Fiery Strike (Devil Only) | 2d6 + 3 + summonSpellLevel Fire | - | - |


**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (round down).

**Bite (Demon Only).** {@atkr m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 5 ft. {@h}{@damage 1d12 + 3 + summonSpellLevel} Necrotic damage.

**Claws (Yugoloth Only).** {@atkr m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 5 ft. {@h}{@damage 1d8 + 3 + summonSpellLevel} Slashing damage. Immediately after the attack hits or misses, the spirit can teleport up to 30 feet to an unoccupied space it can see.

**Fiery Strike (Devil Only).** {@atkr m,r} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 5 ft. or range 150 ft. {@h}{@damage 2d6 + 3 + summonSpellLevel} Fire damage.

^Tags: #monster #type_fiend