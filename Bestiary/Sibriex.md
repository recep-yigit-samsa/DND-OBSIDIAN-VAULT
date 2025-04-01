# Sibriex

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sibriex | Unknown | 18 | 150 (12d12 + 72) | 19 | walk: 0 ft., fly: {'number': 20, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Chain | 2d12 + 7 | - | - |
| Bite | 2d8 + 2d8 | - | - |
| Squirt Bile | 10d6 | 20 | - |
| Warp Creature | - | 20 | - |


**Multiattack.** The sibriex uses Squirt Bile once and makes three attacks using its chain, bite, or both.

**Chain.** {@atk mw} {@hit 6} to hit, reach 15 ft., one target. {@h}20 ({@damage 2d12 + 7}) piercing damage.

**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d8}) piercing damage plus 9 ({@damage 2d8}) acid damage.

**Squirt Bile.** The sibriex targets one creature it can see within 120 feet of it. The target must succeed on a {@dc 20} Dexterity saving throw or take 35 ({@damage 10d6}) acid damage.

**Warp Creature.** The sibriex targets up to three creatures it can see within 120 feet of it. Each target must make a {@dc 20} Constitution saving throw. On a successful save, a creature becomes immune to this sibriex's Warp Creature. On a failed save, the target is {@condition poisoned}, which causes it to also gain 1 level of {@condition exhaustion}. While {@condition poisoned} in this way, the target must repeat the saving throw at the start of each of its turns. Three successful saves against the poison end it, and ending the poison removes any levels of {@condition exhaustion} caused by it. Each failed save causes the target to suffer another level of {@condition exhaustion}. Once the target reaches 6 levels of {@condition exhaustion}, it dies and instantly transforms into a living {@creature abyssal wretch|mtf} under the sibriex's control. The transformation of the body can be undone only by a {@spell wish} spell.

^Tags: #monster #type_unknown