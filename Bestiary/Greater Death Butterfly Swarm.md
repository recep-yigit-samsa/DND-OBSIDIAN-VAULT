# Greater Death Butterfly Swarm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Greater Death Butterfly Swarm | Unknown | 6 | 84 (13d12) | 15 | walk: 5 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bites | 6d6 + 3d6 + 3d6 | 15 | - |


**Multiattack.** The swarm makes two Bites attacks.

**Bites.** {@atk mw} {@hit 7} to hit, reach 0 ft., one creature in the swarm's space. {@h}21 ({@damage 6d6}) piercing damage, or 10 ({@damage 3d6}) piercing damage if the swarm has half of its hp or fewer. The target must make a {@dc 15} Constitution saving throw. On a failure, it takes 10 ({@damage 3d6}) poison damage and is {@condition poisoned} for 1 minute. On a success, it takes half the damage and isn't {@condition poisoned}. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown