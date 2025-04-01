# Draconic Spirit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Draconic Spirit | Dragon | N/A | 50 + 10 for each spell level above 5 |  | walk: 30 ft., fly: 60 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d6 + 4 + summonSpellLevel Piercing | - | - |
| Breath Weapon | 2d6 | - | Half Damage ✅ |


**Multiattack.** The spirit makes a number of Rend attacks equal to half the spell's level (round down), and it uses Breath Weapon.

**Rend.** {@atk m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 10 feet. {@h}{@damage 1d6 + 4 + summonSpellLevel} Piercing damage.

**Breath Weapon.** {@actSave dex} DC equals your spell save DC, each creature in a 30-foot Cone. {@actSaveFail} {@damage 2d6} damage of a type this spirit has Resistance to (your choice when you cast the spell). {@actSaveSuccess} Half damage.

^Tags: #monster #type_dragon