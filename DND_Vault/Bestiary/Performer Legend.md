# Performer Legend

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Performer Legend | humanoid | 10 | 162 (25d8 + 50) | 20 | walk 30 |

## Abilities

- **STR** 12 | **DEX** 20 | **CON** 14 | **INT** 15 | **WIS** 16 | **CHA** 20
- **Saving Throws:** DEX ++9, INT ++6, WIS ++7, CHA ++9  
- **Skills:** Acrobatics ++13, Athletics ++5, Perception ++7, Performance ++13, Stealth ++9  
- **Damage Resistances:** -  
- **Condition Immunities:** -  
- **Senses:** -  
- **Languages:** Common plus two other languages


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Bejeweled Baton | +9 to hit | 2d4 + 5 damage) Bludgeoning damage plus 10 (3d6 damage) Psychic | - |
| Majestic Song | DC 17 | 4d8 + 4 damage) Psychic | Half Damage ✅ |

**Multiattack.** The performer makes three Bejeweled Baton attacks.

**Bejeweled Baton.** {@atkr m} +9 to hit, reach 5 ft. {@h}10 (2d4 + 5 damage) Bludgeoning damage plus 10 (3d6 damage) Psychic damage.

**Majestic Song.** {@actSave wis} DC 17 Saving Throw, each creature in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point within 120 feet. {@actSaveFail} 22 (4d8 + 4 damage) Psychic damage, and the target has the Charmed|XPHB condition or Frightened|XPHB condition condition (performer's choice) until the end of the performer's next turn. {@actSaveSuccess} Half damage only.

## Reactions

**Warding Charm.** {@actTrigger} A creature hits the performer with an attack roll. {@actResponse d}{@actSave wis} DC 17 Saving Throw, the triggering creature. {@actSaveFail} The attack roll misses the performer, and the target has the Charmed|XPHB condition condition until the end of the performer's next turn.



^Tags: #combat_ready #monster #type_humanoid #cr_10