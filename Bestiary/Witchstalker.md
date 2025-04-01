# Witchstalker

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Witchstalker | Monstrosity | 6 | 82 (11d10 + 22) | 13 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d6 + 4 | 15 | - |
| Mind-Wracking Howl {@recharge 5} | 7d6 | 13 | - |


**Multiattack.** The witchstalker makes two Bite attacks.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}14 ({@damage 3d6 + 4}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 15} Strength saving throw or have the {@condition prone} condition.

**Mind-Wracking Howl {@recharge 5}.** The witchstalker unleashes a terrible howl, and each creature within 30 feet of it that isn't a Monstrosity must make a {@dc 13} Wisdom saving throw. On a failed save, a creature takes 24 ({@damage 7d6}) psychic damage and has disadvantage on Constitution saving throws to maintain {@status concentration} on spells until the end of its next turn. On a successful save, a creature takes half as much damage only.

^Tags: #monster #type_monstrosity