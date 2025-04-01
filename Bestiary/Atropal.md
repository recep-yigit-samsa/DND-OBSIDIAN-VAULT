# Atropal

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Atropal | Unknown | 13 | 225 (18d12 + 108) | 7 | walk: 0 ft., fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Touch | 3d6 | - | - |
| Ray of Cold | 6d6 | - | - |
| Life Drain | 8d8 | 19 | - |
| Summon Wraith {@recharge} | - | - | - |


**Touch.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}10 ({@damage 3d6}) necrotic damage.

**Ray of Cold.** {@atk rs} {@hit 12} to hit, range 120 ft., one target. {@h}21 ({@damage 6d6}) cold damage.

**Life Drain.** The atropal targets one creature it can see within 120 feet of it. The target must succeed on a {@dc 19} Constitution saving throw, taking 36 ({@damage 8d8}) necrotic damage on a failed save, or half as much damage on a successful one. The atropal regains a number of hit points equal to half the amount of damage dealt.

**Summon Wraith {@recharge}.** The atropal summons a {@creature wraith} which materializes within 30 feet of it in an unoccupied space it can see. The wraith obeys its summoner's commands and can't be controlled by any other creature. The Wraith vanishes when it drops to 0 hit points or when its summoner dies.

^Tags: #monster #type_unknown