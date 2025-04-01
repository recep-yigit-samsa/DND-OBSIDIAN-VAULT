# Grell Psychic

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Grell Psychic | Aberration | 4 | 66 (12d8 + 12) | 12, 15 | walk: 10 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Beak | 3d4 + 3 | - | - |
| Tentacle | 1d10 + 3 | 11 | - |


**Multiattack.** The grell psychic makes one Tentacle attack and one Beak attack.

**Beak.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}10 ({@damage 3d4 + 3}) piercing damage.

**Tentacle.** {@atk mw} {@hit 5} to hit, reach 10 ft., one target. {@h}8 ({@damage 1d10 + 3}) piercing damage, and the target must succeed on a {@dc 11} Constitution saving throw or have the {@condition poisoned} condition for 1 minute. While the target is {@condition poisoned}, it also has the {@condition paralyzed} condition. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The target also has the {@condition grappled} condition (escape {@dc 16}). While grappling the target, the grell can't make Tentacle attacks against other targets. When the grell moves, any Medium or smaller target it is grappling moves with it.

^Tags: #monster #type_aberration