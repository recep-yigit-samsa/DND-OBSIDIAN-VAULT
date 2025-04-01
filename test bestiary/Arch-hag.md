# Arch-hag

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Arch-hag | fey | {'cr': '21', 'xpLair': 41000} | 333 (29d10 + 174) | 20 | walk 40 |

## Abilities

- **STR** 24 | **DEX** 15 | **CON** 23 | **INT** 19 | **WIS** 19 | **CHA** 25
- **Saving Throws:** DEX ++9, WIS ++11  
- **Skills:** Deception ++14, Perception ++11, Persuasion ++21  
- **Damage Resistances:** cold, fire, psychic  
- **Condition Immunities:** charmed, exhaustion, frightened  
- **Senses:** truesight 60 ft.  
- **Languages:** all

## Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the hag fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The hag has {@variantrule Advantage|XPHB} on saving throws against spells and other magical effects.

**Spiteful Escape.** When the hag drops to 0 {@variantrule Hit Points|XPHB}, it dies only if it is within 30 feet of its anathema (a thing the DM chooses as the hag's most hated thing). Otherwise, the hag drops to 1 {@variantrule Hit Points|XPHB|Hit Point} and teleports to a harmless demiplane, and it can't return to the plane it left for {@dice 2d6} days. When the hag teleports away, each creature within 60 feet of the space it left is cursed. Until the curse ends, a creature has {@variantrule Disadvantage|XPHB} on ability checks and saving throws, and the hag knows its location anywhere in the multiverse.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Spectral Claw | +14 to hit | 3d6 + 7 damage) Force | - |
| Crackling Wave | DC 22 | 5d12 damage) Lightning | Half Damage ✅ |

**Multiattack.** The hag makes two Spectral Claw attacks and uses Crackling Wave.

**Spectral Claw.** {@atkr m,r} +14 to hit, reach 10 ft. or range 60 ft. {@h}17 (3d6 + 7 damage) Force damage. If the target is a Large or smaller creature, it has the Prone|XPHB condition condition.

**Crackling Wave.** {@actSave dex} DC 22 Saving Throw, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 32 (5d12 damage) Lightning damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} The target is cursed until the end of the hag's next turn. The target can't take Reactions until the curse ends.

## Legendary Actions

**Hag's Swipe.** The hag makes one Spectral Claw attack.

**Malicious Magic.** The hag uses Spellcasting to cast Dimension Door|XPHB spell or Hypnotic Pattern|XPHB spell. The hag can't take this action again until the start of its next turn.



^Tags: #combat_ready #monster #type_fey #cr_{'cr': '21', 'xpLair': 41000} #legendary