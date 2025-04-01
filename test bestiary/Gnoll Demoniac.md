# Gnoll Demoniac

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gnoll Demoniac | fiend | 8 | 135 (18d8 + 54) | 16 | walk 30 |

## Abilities

- **STR** 16 | **DEX** 12 | **CON** 17 | **INT** 14 | **WIS** 15 | **CHA** 17
- **Saving Throws:** STR ++6, CON ++6, WIS ++5, CHA ++6  
- **Skills:** Perception ++5  
- **Damage Resistances:** -  
- **Condition Immunities:** -  
- **Senses:** darkvision 60 ft.  
- **Languages:** Abyssal, Common, Gnoll


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Abyssal Strike | +6 to hit | 5d6 + 3 damage) Poison | - |
| Hunger of Yeenoghu {@recharge 5} | DC 14 | 8d6 damage) Necrotic | Half Damage ✅ |

**Multiattack.** The gnoll makes two Abyssal Strike attacks.

**Abyssal Strike.** {@atkr m,r} +6 to hit, reach 5 ft. or range 60 ft. {@h}20 (5d6 + 3 damage) Poison damage.

**Hunger of Yeenoghu {@recharge 5}.** The gnoll conjures a 30-foot {@variantrule Cube [Area of Effect]|XPHB|Cube} of magical {@variantrule Darkness|XPHB} originating from a point it can see within 60 feet, which lasts for 1 minute or until the gnoll's {@status Concentration|XPHB} ends on it. This area is {@variantrule Difficult Terrain|XPHB}. {@actSave dex} DC 14 Saving Throw, any creature that starts its turn in this area or enters it for the first time on a turn. {@actSaveFail} 28 (8d6 damage) Necrotic damage, and the gnoll or a creature of its choice it can see gains 10 {@variantrule Temporary Hit Points|XPHB}. {@actSaveSuccess} Half damage only.


^Tags: #combat_ready #monster #type_fiend #cr_8