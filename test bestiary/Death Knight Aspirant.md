# Death Knight Aspirant

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Death Knight Aspirant | undead | 11 | 178 (21d8 + 84) | 20 | walk 30 |

## Abilities

- **STR** 20 | **DEX** 10 | **CON** 18 | **INT** 10 | **WIS** 12 | **CHA** 16
- **Saving Throws:** DEX ++4, WIS ++5  
- **Skills:** -  
- **Damage Resistances:** -  
- **Condition Immunities:** exhaustion, frightened, poisoned  
- **Senses:** darkvision 120 ft.  
- **Languages:** Abyssal, Common

## Traits

**Magic Resistance.** The aspirant has {@variantrule Advantage|XPHB} on saving throws against spells and other magical effects.

**Marshal Undead.** Undead creatures of the aspirant's choice (excluding itself) in a 60-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from it have {@variantrule Advantage|XPHB} on attack rolls and saving throws. It can't use this trait if it has the Incapacitated|XPHB condition condition.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Dread Blade | +9 to hit | 2d8 + 5 damage) Slashing damage plus 10 (3d6 damage) Necrotic | - |
| Hellfire Orb {@recharge 5} | DC 15 | 6d6 damage) Fire damage plus 21 (6d6 damage) Necrotic | Half Damage ✅ |

**Multiattack.** The aspirant makes three Dread Blade attacks.

**Dread Blade.** {@atkr m} +9 to hit, reach 5 ft. {@h}14 (2d8 + 5 damage) Slashing damage plus 10 (3d6 damage) Necrotic damage.

**Hellfire Orb {@recharge 5}.** {@actSave dex} DC 15 Saving Throw, each creature in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point the aspirant can see within 120 feet of itself. {@actSaveFail} 21 (6d6 damage) Fire damage plus 21 (6d6 damage) Necrotic damage. {@actSaveSuccess} Half damage.

## Reactions

**Parry.** {@actTrigger} The aspirant is hit by a melee attack roll while holding a weapon. {@actResponse} The aspirant adds 4 to its AC against that attack, possibly causing it to miss.



^Tags: #combat_ready #monster #type_undead #cr_11