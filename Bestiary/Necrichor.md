# Necrichor

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Necrichor | Undead | 7 | 67 (9d8 + 27) | 12 | walk: 20 ft., climb: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pseudopod | 1d6 + 2 | 14 | - |
| Necrotic Bolt | 2d8 + 3 | - | - |
| Blood Puppeteering {@recharge} | - | 14 | Half Damage ✅ |


**Multiattack.** The necrichor makes two attacks.

**Pseudopod.** {@atk mw} {@hit 5} to hit, reach 10 ft., one target. {@h}5 ({@damage 1d6 + 2}) necrotic damage, and the target must succeed on a {@dc 14} Constitution saving throw or be {@condition paralyzed} until the start of the necrichor's next turn.

**Necrotic Bolt.** {@atk rs} {@hit 6} to hit, range 120 ft., one creature. {@h}12 ({@damage 2d8 + 3}) necrotic damage, and the target can't regain hit points until the start of the necrichor's next turn.

**Blood Puppeteering {@recharge}.** The necrichor targets a creature it can see within 5 feet of it that is missing any of its hit points. If the target isn't a Construct or an Undead, it must succeed on a {@dc 14} Constitution saving throw or the necrichor enters the target's space and attaches itself to the target for 1 minute. While attached, the necrichor takes only half damage dealt to it (round down), and the target takes the remaining damage. The necrichor can attach to only one creature at a time. The attached necrichor can telepathically control the target's move, action, or both. When controlled this way, the target can take only the Attack action (necrichor chooses the target) or the Dash action. The attached target can repeat the saving throw at the end of each of its turns, detaching from the necrichor and forcing it to move into the nearest unoccupied space on a success.

^Tags: #monster #type_undead