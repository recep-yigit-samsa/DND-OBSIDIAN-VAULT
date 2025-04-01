# Oculo Swarm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Oculo Swarm | Unknown | 4 | 82 (11d10 + 22) | 15 | walk: 5 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 13 | - |
| Extract Eye | 4d8 + 2d8 | - | - |
| Disorienting Gaze {@recharge 5} | 6d6 | 13 | - |


**Multiattack.** The oculo swarm makes two Extract Eye attacks. If both attacks hit one creature, the target must succeed on a {@dc 13} Strength saving throw or the swarm removes one of its eyes. While missing half or fewer of its total number of eyes, the target has disadvantage on attack rolls and Wisdom ({@skill Perception}) checks that rely on sight. While missing more than half its total number of eyes, the target is {@condition blinded} until its sight is restored. If the target's eye is recovered from the defeated swarm, it can be reattached with a successful {@dc 12} Wisdom ({@skill Medicine}) check, provided the eye is reattached within 1 hour of the target losing the eye.

**Extract Eye.** {@atk mw} {@hit 7} to hit, reach 0 ft., one creature in the swarm's space. {@h}18 ({@damage 4d8}) piercing damage, or 9 ({@damage 2d8}) piercing damage if the swarm has half of its hp or fewer.

**Disorienting Gaze {@recharge 5}.** The swarm's many eyes suddenly turn in different directions. Each creature within 10 feet of the oculo swarm must make a {@dc 13} Charisma saving throw. On a failure, a creature takes 21 ({@damage 6d6}) psychic damage and is disoriented until the end of its next turn. On a success, a creature takes half the damage and isn't disoriented. A disoriented creature is {@condition incapacitated} and moves in a random direction when it moves.

^Tags: #monster #type_unknown