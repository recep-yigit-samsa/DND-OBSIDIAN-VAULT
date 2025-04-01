# Undead Spirit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Undead Spirit | Undead | N/A | 30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3 |  | walk: 30 ft., fly: {'number': 40, 'condition': '(hover; Ghostly only)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Deathly Touch (Ghostly Only) | 1d8 + 3 + summonSpellLevel Necrotic | - | - |
| Grave Bolt (Skeletal Only) | 2d4 + 3 + summonSpellLevel Necrotic | - | - |
| Rotting Claw (Putrid Only) | 1d6 + 3 + summonSpellLevel Slashing | - | - |


**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (round down).

**Deathly Touch (Ghostly Only).** {@atkr m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 5 ft. {@h}{@damage 1d8 + 3 + summonSpellLevel} Necrotic damage, and the target has the {@condition Frightened|XPHB} condition until the end of its next turn.

**Grave Bolt (Skeletal Only).** {@atkr r} {@hitYourSpellAttack Bonus equals your spell attack modifier}, range 150 ft. {@h}{@damage 2d4 + 3 + summonSpellLevel} Necrotic damage.

**Rotting Claw (Putrid Only).** {@atkr m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 5 ft. {@h}{@damage 1d6 + 3 + summonSpellLevel} Slashing damage. If the target has the {@condition Poisoned|XPHB} condition, it has the {@condition Paralyzed|XPHB} condition until the end of its next turn.

^Tags: #monster #type_undead