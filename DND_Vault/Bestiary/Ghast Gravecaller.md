# Ghast Gravecaller

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ghast Gravecaller | undead | 6 | 97 (15d8 + 30) | 16 | walk 30 |

## Abilities

- **STR** 16 | **DEX** 17 | **CON** 14 | **INT** 18 | **WIS** 14 | **CHA** 8
- **Saving Throws:** CON ++5, WIS ++5  
- **Skills:** -  
- **Damage Resistances:** -  
- **Condition Immunities:** charmed, exhaustion, poisoned  
- **Senses:** darkvision 120 ft.  
- **Languages:** Abyssal, Common

## Traits

**Stench.** {@actSave con} DC 13 Saving Throw, any creature that starts its turn in a 5-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the ghast. {@actSaveFail} The target has the Poisoned|XPHB condition condition until the start of its next turn. {@actSaveSuccess} The target is immune to this ghast's Stench for 24 hours.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Claw | +6 to hit | 3d6 + 3 damage) Slashing | - |
| Horrific Necrosis | +7 to hit | 2d10 + 4 damage) Necrotic | - |

**Multiattack.** The ghast makes two Horrific Necrosis attacks. It can replace one attack with a Claw attack.

**Claw.** {@atkr m} +6 to hit, reach 5 ft. {@h}13 (3d6 + 3 damage) Slashing damage. If the target isn't an Undead, it has the Paralyzed|XPHB condition condition until the end of its next turn.

**Horrific Necrosis.** {@atkr m,r} +7 to hit, reach 5 ft. or range 120 ft. {@h}15 (2d10 + 4 damage) Necrotic damage, and the target has the Frightened|XPHB condition condition until the end of its next turn.


^Tags: #combat_ready #monster #type_undead #cr_6