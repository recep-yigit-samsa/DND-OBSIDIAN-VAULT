# Phylaskia

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Phylaskia | undead | 9 | 104 (11d10 + 44) | 18 | walk 40 |

## Abilities

- **STR** 20 | **DEX** 15 | **CON** 18 | **INT** 10 | **WIS** 16 | **CHA** 14
- **Saving Throws:** CON ++8, WIS ++7  
- **Skills:** Insight ++7, Perception ++7  
- **Damage Resistances:** -  
- **Condition Immunities:** blinded, charmed, deafened, exhaustion, frightened, poisoned  
- **Senses:** truesight 120 ft.  
- **Languages:** all

## Traits

**Gatekeeper's Aura.** Any creature that starts its turn within 10 feet of the phylaskia must make a DC 15 Saving Throw Wisdom saving throw. On a successful save, the creature is immune to this aura for the next 24 hours. On a failed save, the creature has disadvantage on saving throws and its speed is halved until the start of its next turn.

**Undead Fortitude.** If damage reduces the phylaskia to 0 hit points, it must make a Constitution saving throw with a DC equal to 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the phylaskia drops to 1 hit point instead.

**Vigilant.** The phylaskia can't be {@status surprised}.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Longsword | +9 to hit | 2d8 + 5 damage) slashing | - |
| Strength Drain | +9 to hit | 2d6 + 5 damage) necrotic | - |

**Multiattack.** The phylaskia makes two longsword attacks and uses its Strength Drain once.

**Longsword.** {@atk mw} +9 to hit to hit, reach 10 ft., one target. {@h}14 (2d8 + 5 damage) slashing damage, or 16 (2d10 + 5 damage) slashing damage if used with two hands, plus 11 (2d10 damage) necrotic damage.

**Strength Drain.** {@atk mw} +9 to hit to hit, reach 5 ft., one creature. {@h}12 (2d6 + 5 damage) necrotic damage. Unless the target is immune to necrotic damage, its Strength score is reduced by {@dice 1d4}. The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.


^Tags: #combat_ready #monster #type_undead #cr_9