# Cockatrice Regent

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cockatrice Regent | monstrosity | 8 | 136 (16d10 + 48) | 15 | walk 30, fly 60 |

## Abilities

- **STR** 19 | **DEX** 14 | **CON** 16 | **INT** 3 | **WIS** 16 | **CHA** 5
- **Saving Throws:** WIS ++6  
- **Skills:** -  
- **Damage Resistances:** -  
- **Condition Immunities:** petrified  
- **Senses:** darkvision 120 ft.  
- **Languages:** -

## Traits

**Flyby.** The cockatrice doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Petrifying Bite | +7 to hit | 2d8 + 4 damage) Piercing | - |
| Talons | +7 to hit | 4d6 + 4 damage) Slashing | - |

**Multiattack.** The cockatrice makes one Petrifying Bite attack and two Talons attacks.

**Petrifying Bite.** {@atkr m} +7 to hit, reach 5 ft. {@h}13 (2d8 + 4 damage) Piercing damage. If the target is a creature, it is subjected to the following effect. {@actSave con} DC 14 Saving Throw. {@actSaveFail 1} The target has the Restrained|XPHB condition condition and repeats the save at the end of its next turn if it is still Restrained|XPHB condition, ending the effect on itself on a success. {@actSaveFail 2} The target has the Petrified|XPHB condition condition instead of the Restrained|XPHB condition condition.

**Talons.** {@atkr m} +7 to hit, reach 5 ft. {@h}18 (4d6 + 4 damage) Slashing damage.

## Reactions

**Magical Backlash.** {@actTrigger} A creature within 120 feet of the cockatrice deals damage to it. {@actResponse d}{@actSave dex} DC 14 Saving Throw, the triggering creature. {@actSaveFail} 13 (3d6 + 3 damage) Force damage.



^Tags: #combat_ready #monster #type_monstrosity #cr_8