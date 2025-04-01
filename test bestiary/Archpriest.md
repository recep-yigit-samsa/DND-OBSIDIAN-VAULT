# Archpriest

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Archpriest | humanoid | 12 | 240 (32d8 + 96) | 16 | walk 30 |

## Abilities

- **STR** 16 | **DEX** 12 | **CON** 17 | **INT** 14 | **WIS** 21 | **CHA** 14
- **Saving Throws:** STR ++7, CON ++7, INT ++6, WIS ++9  
- **Skills:** Insight ++9, Medicine ++9, Perception ++9, Religion ++10  
- **Damage Resistances:** -  
- **Condition Immunities:** -  
- **Senses:** -  
- **Languages:** Common plus two other languages


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Radiant Burst | +9 to hit | 4d10 + 5 damage) Radiant | - |
| Holy Word {@recharge 4} | DC 17 | 6d6 damage) Radiant | Half Damage ✅ |

**Multiattack.** The archpriest makes three Radiant Burst attacks.

**Radiant Burst.** {@atkr m,r} +9 to hit, reach 5 ft. or range 60 ft. {@h}27 (4d10 + 5 damage) Radiant damage.

**Holy Word {@recharge 4}.** {@actSave wis} DC 17 Saving Throw, each enemy in a 20-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the archpriest. {@actSaveFail} 21 (6d6 damage) Radiant damage, and the target has the Stunned|XPHB condition condition until the end of the archpriest's next turn. {@actSaveSuccess} Half damage only.


^Tags: #combat_ready #monster #type_humanoid #cr_12