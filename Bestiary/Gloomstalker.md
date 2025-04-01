# Gloomstalker

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gloomstalker | Monstrosity | 6 | 90 (12d10 + 24) | 15 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 6 + 2d6 | - | - |
| Claws | 2d6 + 6 + 2d6 | - | - |
| Snatch | 2d6 + 6 + 2d6 | 17 | - |
| Shriek {@recharge} | - | 13 | - |


**Multiattack.** The gloomstalker makes two attacks: one with its bite and one with its claws.

**Bite.** {@atk mw} {@hit 9} to hit, reach 5 ft., one creature. {@h}15 ({@damage 2d8 + 6}) piercing damage plus 7 ({@damage 2d6}) necrotic damage.

**Claws.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage plus 7 ({@damage 2d6}) necrotic damage.

**Snatch.** {@atk mw} {@hit 9} to hit, reach 5 ft., one Medium or smaller creature. {@h}13 ({@damage 2d6 + 6}) slashing damage plus 7 ({@damage 2d6}) necrotic damage, and the target is {@condition grappled} (escape {@dc 17}). While {@condition grappled} in this way, the target is {@condition restrained}.

**Shriek {@recharge}.** The gloomstalker emits a terrible shriek. Each enemy within 60 feet of the gloomstalker that can hear it must succeed on a {@dc 13} Constitution saving throw or be {@condition paralyzed} until the end of the enemy's next turn.

^Tags: #monster #type_monstrosity