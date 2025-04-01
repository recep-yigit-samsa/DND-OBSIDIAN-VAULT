# Gulthias Blight

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gulthias Blight | plant | 16 | 264 (16d20 + 96) | 20 | walk 50 |

## Abilities

- **STR** 25 | **DEX** 10 | **CON** 22 | **INT** 10 | **WIS** 18 | **CHA** 12
- **Saving Throws:** -  
- **Skills:** Perception ++9  
- **Damage Resistances:** fire, necrotic  
- **Condition Immunities:** deafened  
- **Senses:** blindsight 120 ft.  
- **Languages:** Common, Druidic

## Traits

**Blight Seeds.** When it finishes a {@variantrule Long Rest|XPHB}, the blight expels {@dice 1d6} seeds into unoccupied spaces on the ground within 30 feet of itself. After 24 hours, the seeds become creatures under the blight's control. Roll {@dice 1d8} for each seed to determine the creature it becomes: on 1-4, Twig Blight|XMM; on 5-6, Needle Blight|XMM; on 7-8, Vine Blight|XMM.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Slam | +12 to hit | 4d8 + 7 damage) Bludgeoning | - |
| Thorn Volley | +12 to hit | 3d8 + 7 damage) Piercing | - |
| Life-Draining Root | DC 20 | 2d6 + 7 damage) Necrotic | - |

**Multiattack.** The blight makes two attacks, using Slam or Thorn Volley in any combination. It also uses Life-Draining Root.

**Slam.** {@atkr m} +12 to hit, reach 10 ft. {@h}25 (4d8 + 7 damage) Bludgeoning damage.

**Thorn Volley.** {@atkr r} +12 to hit, range 60/180 ft. {@h}20 (3d8 + 7 damage) Piercing damage.

**Life-Draining Root.** {@actSave con} DC 20 Saving Throw, one Huge or smaller creature the blight can see within 30 feet. {@actSaveFail} 14 (2d6 + 7 damage) Necrotic damage, and the target has the Grappled|XPHB condition condition (escape DC 17 Saving Throw) from one of six roots. Until the grapple ends, the target has the Restrained|XPHB condition condition and takes 14 (4d6 damage) Necrotic damage at the start of each of its turns. The target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by an amount equal to the Necrotic damage taken, and the blight regains {@variantrule Hit Points|XPHB} equal to that amount.


^Tags: #combat_ready #monster #type_plant #cr_16