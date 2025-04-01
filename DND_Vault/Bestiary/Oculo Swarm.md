# Oculo Swarm

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Oculo Swarm | aberration | 4 | 82 (11d10 + 22) | 15 | walk 5, canHover True |

## Abilities

- **STR** 10 | **DEX** 20 | **CON** 14 | **INT** 8 | **WIS** 15 | **CHA** 17
- **Saving Throws:** -  
- **Skills:** Insight ++6, Perception ++6, Stealth ++7  
- **Damage Resistances:** bludgeoning, piercing, slashing  
- **Condition Immunities:** charmed, frightened, grappled, paralyzed, petrified, prone, restrained, stunned  
- **Senses:** darkvision 60 ft.  
- **Languages:** understands Common but can't speak

## Traits

**Hundreds of Eyes.** The oculo swarm has advantage on Wisdom ({@skill Perception}) checks that rely on sight and on saving throws against being blinded condition. In addition, if the swarm isn't blinded condition, creatures attacking it can't benefit from traits and features that rely on a creature's allies distracting or surrounding the swarm, such as the Pack Tactics trait or Sneak Attack class feature.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny eyeball. The swarm can't regain hp or gain temporary hp.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Multiattack | DC 13 | - | - |
| Extract Eye | +7 to hit | 4d8 damage) piercing | - |
| Disorienting Gaze {@recharge 5} | DC 13 | 6d6 damage) psychic | - |

**Multiattack.** The oculo swarm makes two Extract Eye attacks. If both attacks hit one creature, the target must succeed on a DC 13 Saving Throw Strength saving throw or the swarm removes one of its eyes. While missing half or fewer of its total number of eyes, the target has disadvantage on attack rolls and Wisdom ({@skill Perception}) checks that rely on sight. While missing more than half its total number of eyes, the target is blinded condition until its sight is restored. If the target's eye is recovered from the defeated swarm, it can be reattached with a successful DC 12 Saving Throw Wisdom ({@skill Medicine}) check, provided the eye is reattached within 1 hour of the target losing the eye.

**Extract Eye.** {@atk mw} +7 to hit to hit, reach 0 ft., one creature in the swarm's space. {@h}18 (4d8 damage) piercing damage, or 9 (2d8 damage) piercing damage if the swarm has half of its hp or fewer.

**Disorienting Gaze {@recharge 5}.** The swarm's many eyes suddenly turn in different directions. Each creature within 10 feet of the oculo swarm must make a DC 13 Saving Throw Charisma saving throw. On a failure, a creature takes 21 (6d6 damage) psychic damage and is disoriented until the end of its next turn. On a success, a creature takes half the damage and isn't disoriented. A disoriented creature is incapacitated condition and moves in a random direction when it moves.


^Tags: #combat_ready #monster #type_aberration #cr_4