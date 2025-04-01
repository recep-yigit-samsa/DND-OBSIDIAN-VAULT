# Colossus

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Colossus | construct | 25 | 553 (27d20 + 270) | 23 | walk 60 |

## Abilities

- **STR** 30 | **DEX** 11 | **CON** 30 | **INT** 3 | **WIS** 11 | **CHA** 8
- **Saving Throws:** DEX ++8, WIS ++8  
- **Skills:** -  
- **Damage Resistances:** necrotic, radiant  
- **Condition Immunities:** charmed, exhaustion, frightened, paralyzed, petrified, poisoned, stunned, unconscious  
- **Senses:** truesight 300 ft.  
- **Languages:** understands Celestial and Common but can't speak

## Traits

**Immutable Form.** The colossus can't shape-shift.

**Legendary Resistance (4/Day).** If the colossus fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The colossus has {@variantrule Advantage|XPHB} on saving throws against spells and other magical effects.

**Siege Monster.** The colossus deals double damage to objects and structures.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Slam | +18 to hit | 4d10 + 10 damage) Bludgeoning | - |
| Radiant Ray | +18 to hit | 4d10 damage) Radiant | - |
| Divine Beam {@recharge 5} | DC 26 | 10d12 damage) Radiant | Half Damage ✅ |

**Multiattack.** The colossus makes three attacks, using Slam or Radiant Ray in any combination.

**Slam.** {@atkr m} +18 to hit, reach 20 ft. {@h}32 (4d10 + 10 damage) Bludgeoning damage, and the colossus pushes the target up to 20 feet straight away from itself.

**Radiant Ray.** {@atkr r} +18 to hit, range 300 ft. {@h}22 (4d10 damage) Radiant damage. If the target is a Large or smaller creature, it has the Prone|XPHB condition condition.

**Divine Beam {@recharge 5}.** {@actSave dex} DC 26 Saving Throw, each creature in a 300-foot-long, 10-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 65 (10d12 damage) Radiant damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} A creature reduced to 0 {@variantrule Hit Points|XPHB} by this beam disintegrates into dust, leaving behind any magic items it was wearing or carrying.

## Legendary Actions

**Smite.** The colossus makes one Radiant Ray attack.

**Stomp.** The colossus moves up to half its {@variantrule Speed|XPHB} without provoking Opportunity Attacks, and it can make one Slam attack at any point during that move.



^Tags: #combat_ready #monster #type_construct #cr_25 #legendary