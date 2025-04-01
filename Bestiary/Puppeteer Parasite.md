# Puppeteer Parasite

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Puppeteer Parasite | Aberration | 3 | 71 (11d4 + 44) | 15 | walk: 10 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Cling | 3d6 + 2 | 14 | - |
| Consume Life | 3d6 + 2 | - | - |


**Cling.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature. {@h}12 ({@damage 3d6 + 2}) necrotic damage, and the parasite attaches to the target. While attached, the parasite can't make Cling attacks. The parasite can detach itself by spending 5 feet of its movement. As an action, a creature within reach of the parasite can try to detach it, doing so with a successful {@dc 14} Strength check.

**Consume Life.** The parasite deals 12 ({@damage 3d6 + 2}) necrotic damage to one creature it is physically attached to, provided that creature isn't a Construct or an Undead. The parasite regains hit points equal to the damage taken.

^Tags: #monster #type_aberration