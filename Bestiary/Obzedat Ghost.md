# Obzedat Ghost

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Obzedat Ghost | Undead | 8 | 110 (20d8 + 20) | 14 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Life Drain | 4d8 | 13 | - |
| Convene the Ghost Council | - | - | - |


**Life Drain.** {@atk mw} {@hit 8} to hit, reach 5 ft., one creature. {@h}18 ({@damage 4d8}) necrotic damage, and the ghost regains hit points equal to half the amount of damage the target takes. The target must succeed on a {@dc 13} Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. The target dies if its hit point maximum is reduced to 0. This reduction to the target's hit point maximum lasts until the target finishes a long rest.

**Convene the Ghost Council.** The ghost summons the other four members of the Obzedat. At the start of the ghost's next turn, the other members appear in unoccupied spaces within 30 feet of the summoner. The ghosts each roll initiative when they appear.

^Tags: #monster #type_undead