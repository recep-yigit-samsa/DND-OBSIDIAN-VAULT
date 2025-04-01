# Gas Spore Fungus

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gas Spore Fungus | plant | 1/2 | 13 (9d10 - 36) | 8 | walk 5, canHover True |

## Abilities

- **STR** 5 | **DEX** 1 | **CON** 3 | **INT** 1 | **WIS** 1 | **CHA** 1
- **Saving Throws:** -  
- **Skills:** -  
- **Damage Resistances:** -  
- **Condition Immunities:** blinded, charmed, deafened, frightened, paralyzed, poisoned, prone  
- **Senses:** blindsight 30 ft.  
- **Languages:** -

## Traits

**Death Burst.** The gas spore bursts when it dies. {@actSave con} DC 10 Saving Throw, each creature in a 20-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the gas spore. {@actSaveFail} The target takes 10 (3d6 damage) Poison damage and has the Poisoned|XPHB condition condition for {@dice 1d12} hours. Unless the Poisoned|XPHB condition condition is removed, the target dies at the end of that time and sprouts {@dice 2d4} Tiny Gas Spore Fungi (each with 1 {@variantrule Hit Points|XPHB|Hit Point}). After {@dice 2d6} days, they become Large and have 13 {@variantrule Hit Points|XPHB}.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Tendril | +0 to hit | 1d6 damage) Poison | - |

**Tendril.** {@atkr m} +0 to hit, reach 5 ft. {@h}3 (1d6 damage) Poison damage, and the target has the Poisoned|XPHB condition condition until the end of its next turn.


^Tags: #combat_ready #monster #type_plant #cr_1/2