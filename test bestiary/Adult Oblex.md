# Adult Oblex

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Oblex | ooze | 5 | 75 (10d8 + 30) | 14 | walk 20 |

## Abilities

- **STR** 8 | **DEX** 19 | **CON** 16 | **INT** 19 | **WIS** 12 | **CHA** 15
- **Saving Throws:** INT ++7, CHA ++5  
- **Skills:** Deception ++5, Perception ++4, Other +[{'oneOf': {'arcana': '+7', 'history': '+7', 'nature': '+7', 'religion': '+7'}}]  
- **Damage Resistances:** -  
- **Condition Immunities:** blinded, charmed, deafened, exhaustion, prone  
- **Senses:** blindsight 60 ft. (blind beyond this distance)  
- **Languages:** Common plus two more languages

## Traits

**Amorphous.** The oblex can move through a space as narrow as 1 inch wide without squeezing.

**Aversion to Fire.** If the oblex takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.

**Sulfurous Impersonation.** As a bonus action, the oblex can extrude a piece of itself that assumes the appearance of one Medium or smaller creature whose memories it has stolen. This simulacrum appears, feels, and sounds exactly like the creature it impersonates, though it smells faintly of sulfur. The oblex can impersonate {@dice 1d4 + 1} different creatures, each one tethered to its body by a strand of slime that can extend up to 120 feet away. For all practical purposes, the simulacrum is the oblex, meaning that the oblex occupies its space and the simulacrum's space simultaneously. The slimy tether is immune to damage, but it is severed if there is no opening at least 1 inch wide between the oblex's main body and the simulacrum. The simulacrum disappears if the tether is severed.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | - | - | - |
| Pseudopod | +7 to hit | 1d6 + 4 damage) bludgeoning damage plus 5 (2d4 damage) psychic | - |
| Eat Memories | DC 15 | 4d8 damage) psychic | - |

**Multiattack.** The oblex makes one pseudopod attack and uses Eat Memories.

**Pseudopod.** {@atk mw} +7 to hit to hit, reach 5 ft., one target. {@h}7 (1d6 + 4 damage) bludgeoning damage plus 5 (2d4 damage) psychic damage.

**Eat Memories.** The oblex targets one creature it can see within 5 feet of it. The target must succeed on a DC 15 Saving Throw Wisdom saving throw or take 18 (4d8 damage) psychic damage and become memory drained until it finishes a short or long rest or until it benefits from the greater restoration spell or heal spell spell. Constructs, oozes, plants, and undead succeed on the save automatically.

While memory drained, the target must roll a {@dice d4} and subtract the number rolled from any ability check or attack roll it makes. Each time the target is memory drained beyond the first, the die size increases by one: the {@dice d4} becomes a {@dice d6}, the {@dice d6} becomes a {@dice d8}, and so on until the die becomes a {@dice d20}, at which point the target becomes unconscious condition for 1 hour. The effect then ends.

When an oblex causes a target to become memory drained, the oblex learns all the languages the target knows and gains all its proficiencies, except for any saving throw proficiencies.


^Tags: #combat_ready #monster #type_ooze #cr_5