# Whirling Chandelier

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Whirling Chandelier | construct | 7 | 105 (14d10 + 28) | 13 | walk 30, canHover True |

## Abilities

- **STR** 18 | **DEX** 15 | **CON** 15 | **INT** 3 | **WIS** 5 | **CHA** 1
- **Saving Throws:** -  
- **Skills:** -  
- **Damage Resistances:** fire  
- **Condition Immunities:** blinded, charmed, deafened, exhaustion, frightened, paralyzed, petrified, poisoned  
- **Senses:** blindsight 60 ft. (blind beyond this radius)  
- **Languages:** understands Common but can't speak

## Traits

**False Appearance.** If the chandelier is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the chandelier move or act, that creature must succeed on a DC 18 Saving Throw Intelligence ({@skill Investigation}) check to discern that the chandelier is animate.

**Fiery Aura.** Any creature that starts its turn within 5 feet of the chandelier takes 7 (2d6 damage) fire damage.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Chain | +7 to hit | 2d8 + 4 damage) bludgeoning | - |
| Lamp | +7 to hit | 2d4 + 4 damage) bludgeoning damage plus 13 (3d8 damage) fire | - |
| Blazing Vortex {@recharge 5} | DC 14 | 8d8 damage) fire | - |

**Multiattack.** The chandelier makes three Chain attacks, three Lamp attacks, or a combination thereof.

**Chain.** {@atk mw} +7 to hit to hit, reach 15 ft., one target. {@h}13 (2d8 + 4 damage) bludgeoning damage, and the target must succeed on a DC 15 Saving Throw Strength saving throw or be pulled into an unoccupied space within 5 feet of the chandelier.

**Lamp.** {@atk mw} +7 to hit to hit, reach 5 ft., one target. {@h}9 (2d4 + 4 damage) bludgeoning damage plus 13 (3d8 damage) fire damage.

**Blazing Vortex {@recharge 5}.** Each creature within 20 feet of the chandelier and not behind {@quickref Cover||3||total cover} must succeed on a DC 14 Saving Throw Constitution saving throw or take 36 (8d8 damage) fire damage and have the blinded condition condition until the start of the chandelier's next turn.


^Tags: #combat_ready #monster #type_construct #cr_7