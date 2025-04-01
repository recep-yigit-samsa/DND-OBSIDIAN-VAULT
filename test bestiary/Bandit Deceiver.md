# Bandit Deceiver

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bandit Deceiver | humanoid | 7 | 130 (20d8 + 40) | 16 | walk 30 |

## Abilities

- **STR** 8 | **DEX** 16 | **CON** 14 | **INT** 17 | **WIS** 12 | **CHA** 16
- **Saving Throws:** DEX ++6, INT ++6  
- **Skills:** Acrobatics ++6, Perception ++4, Stealth ++9  
- **Damage Resistances:** -  
- **Condition Immunities:** -  
- **Senses:** -  
- **Languages:** Common, Thieves' cant


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Dagger | +6 to hit | 2d4 + 3 damage) Piercing damage plus 10 (3d6 damage) Poison | - |
| Blinding Flash {@recharge 4} | DC 14 | 3d6 + 3 damage) Radiant | Half Damage ✅ |

**Multiattack.** The bandit makes three Dagger attacks.

**Dagger.** {@atkr m,r} +6 to hit, reach 5 ft. or range 20/60 ft. {@h}8 (2d4 + 3 damage) Piercing damage plus 10 (3d6 damage) Poison damage.

**Blinding Flash {@recharge 4}.** {@actSave con} DC 14 Saving Throw, each creature in a 10-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point the bandit can see within 120 feet. {@actSaveFail} 13 (3d6 + 3 damage) Radiant damage, and the target has the Blinded|XPHB condition condition until the start of the bandit's next turn. {@actSaveSuccess} Half damage only.


^Tags: #combat_ready #monster #type_humanoid #cr_7