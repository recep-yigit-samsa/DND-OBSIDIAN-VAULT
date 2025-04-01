# Mammon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mammon | Unknown | 26 | 464 (32d12 + 256) | 18 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tail Swipe | 4d10 + 9 | 21 | - |
| Fearful Gaze | 3d12 | 23 | - |
| Constrict | 4d12 + 9 | - | - |
| Golden Gaze {@recharge} | - | 23 | - |


**Multiattack.** Mammon uses Fearful Gaze, then makes four attacks using Tail Swipe, Constrict, or a combination of the two.

**Tail Swipe.** {@atk mw} {@hit 17} to hit, reach 10 ft., one target. {@h}31 ({@damage 4d10 + 9}) bludgeoning damage. If the target is a Large or smaller creature, it has the {@condition grappled} condition (escape {@dc 21}). While {@condition grappled}, the creature also has the {@condition restrained} condition, and Mammon can't make Tail Swipe attacks.

**Fearful Gaze.** Mammon focuses his gaze in a 90-foot cone in front of him. Each creature of his choice within the cone must make a {@dc 23} Wisdom saving throw, taking 19 ({@damage 3d12}) psychic damage on a failed save, or half as much damage on a successful one. Creatures that fail the save have the {@condition frightened} condition until the end of their next turn.

**Constrict.** Mammon tightens his grip around a creature he has {@condition grappled}. The target takes 35 ({@damage 4d12 + 9}) bludgeoning damage.

**Golden Gaze {@recharge}.** Mammon attempts to turn one creature he can see within 60 feet of him into solid gold. The target must make a {@dc 23} Constitution saving throw. On a failed save, the target's flesh begins to harden, and it has the {@condition restrained} condition. A {@condition restrained} creature must repeat the saving throw at the end of each turn. If it successfully saves three times, the effect ends. If it fails three times, it turns to gold and now has the {@condition petrified} condition. Successes and failures don't need to be consecutive.

^Tags: #monster #type_unknown