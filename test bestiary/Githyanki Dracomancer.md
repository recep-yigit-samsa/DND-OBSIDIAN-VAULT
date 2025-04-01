# Githyanki Dracomancer

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Githyanki Dracomancer | aberration | 16 | 255 (30d8 + 120) | 18 | walk 30, canHover True |

## Abilities

- **STR** 10 | **DEX** 16 | **CON** 18 | **INT** 20 | **WIS** 16 | **CHA** 18
- **Saving Throws:** DEX ++8, CON ++9, INT ++10, WIS ++8  
- **Skills:** Arcana ++10, Perception ++8  
- **Damage Resistances:** -  
- **Condition Immunities:** -  
- **Senses:** blindsight 30 ft.  
- **Languages:** Common, Draconic, Gith


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Draconic Strike | +10 to hit | 2d6 + 5 damage) Slashing damage plus 17 (5d6 damage) Fire | - |
| Conjured Dragon's Breath {@recharge 5} | DC 18 | 6d8 damage) Fire damage plus 27 (6d8 damage) Force | Half Damage ✅ |

**Multiattack.** The githyanki makes three Draconic Strike attacks.

**Draconic Strike.** {@atkr m,r} +10 to hit, reach 10 ft. or range 120 ft. {@h}12 (2d6 + 5 damage) Slashing damage plus 17 (5d6 damage) Fire damage, and the target has the Frightened|XPHB condition condition until the start of the githyanki's next turn.

**Conjured Dragon's Breath {@recharge 5}.** {@actSave dex} DC 18 Saving Throw, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 27 (6d8 damage) Fire damage plus 27 (6d8 damage) Force damage. {@actSaveSuccess} Half damage.


^Tags: #combat_ready #monster #type_aberration #cr_16