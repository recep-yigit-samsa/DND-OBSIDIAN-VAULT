# Death Butterfly Swarm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Death Butterfly Swarm | Unknown | 4 | 60 (11d10) | 15 | walk: 5 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bites | 6d6 + 3d6 + 3d6 | 12 | - |


**Bites.** {@atk mw} {@hit 4} to hit, reach 0 ft., one creature in the swarm's space. {@h}21 ({@damage 6d6}) piercing damage, or 10 ({@damage 3d6}) piercing damage if the swarm has half of its hp or fewer. The target must make a {@dc 12} Constitution saving throw. On a failure, it takes 10 ({@damage 3d6}) poison damage and is {@condition poisoned} until the end of its next turn. On a success, it takes half the damage and isn't {@condition poisoned}.

^Tags: #monster #type_unknown