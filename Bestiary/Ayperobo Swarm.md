# Ayperobo Swarm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ayperobo Swarm | Unknown | 12 | 130 (20d8 + 40) | 20 | walk: 5 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 8d4 + 7 + 4d4 + 7 | - | - |
| Burrow {@recharge} | 10d6 + 4d6 | 17 | - |


**Multiattack.** The ayperobo swarm makes three Bite attacks.

**Bite.** {@atk mw} {@hit 11} to hit, reach 0 ft., one target. {@h}27 ({@damage 8d4 + 7}) piercing damage, or 17 ({@damage 4d4 + 7}) piercing damage if the swarm has half of its hit points (65) or fewer.

**Burrow {@recharge}.** The ayperobo swarm makes a Bite attack. On a hit, the swarm burrows inside the creature, dealing an additional 35 ({@damage 10d6}) necrotic damage and taking control of the creature. At the start of each of its turns, the target may make a {@dc 17} Constitution saving throw, expelling the ayperobo swarm and taking 14 ({@damage 4d6}) piercing damage on a success. While burrowed inside a creature, the ayperobo swarm has {@quickref Cover||3||total cover} against attacks targeting them, and no longer acts on their own initiative. Instead, they take total control over their host, gaining all of its abilities, attacks, and equipment. They act during the host's turn, taking actions based on their host. If a host dies while the ayperobo swarm is burrowed, they leave the host at the end of the host's turn, rolling initiative if necessary. Creatures acting as hosts to the ayperobo swarm are fully aware of their actions and surroundings, but are incapable of physically operating their body.

^Tags: #monster #type_unknown