# Elemental Spirit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Elemental Spirit | Elemental | N/A | 50 + 10 for each spell level above 4 |  | walk: 40 ft., burrow: {'number': 40, 'condition': '(Earth only)'} ft., fly: {'number': 40, 'condition': '(hover; Air only)'} ft., swim: {'number': 40, 'condition': '(Water only)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 1d10 + 4 + summonSpellLevel | - | - |


**Multiattack.** The spirit makes a number of Slam attacks equal to half this spell's level (round down).

**Slam.** {@atkr m} {@hitYourSpellAttack Bonus equals your spell attack modifier}, reach 5 ft. {@h}{@damage 1d10 + 4 + summonSpellLevel} Bludgeoning (Earth only), Cold (Water only), Lightning (Air only), or Fire (Fire only) damage.

^Tags: #monster #type_elemental