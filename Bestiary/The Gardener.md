# The Gardener

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| The Gardener | Unknown | 12 | 209 (22d8 + 110) | 17 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Vine | 1d12 + 5 + 2d8 | 17 | - |
| Breath of Tranquility {@recharge 5} | - | 17 | - |


**Multiattack.** The Gardener makes two Vine attacks and can use Breath of Tranquility if available.

**Vine.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}11 ({@damage 1d12 + 5}) bludgeoning damage plus 9 ({@damage 2d8}) psychic damage, and if the target is a Large or smaller creature, the vine wraps around the target, and the target has the {@condition grappled} condition (escape {@dc 17}). The vine vanishes when the target is no longer {@condition grappled}, or when the Gardener wills it to (no action required). A creature reduced to 0 hit points by the vine has the {@condition unconscious} condition but is stable instead of dying.

**Breath of Tranquility {@recharge 5}.** The Gardener exhales soporific vapor in a 30-foot cone. Each creature in that area must succeed on a {@dc 17} Constitution saving throw or have the {@condition poisoned} condition. A {@condition poisoned} creature must repeat the saving throw at the end of its next turn. On a failed save, it has the {@condition unconscious} condition, and on a successful save, the effect ends on it. An {@condition unconscious} creature is no longer {@condition poisoned} and remains {@condition unconscious} for 1 hour, until it takes damage, or until a creature uses an action to shake it awake.

^Tags: #monster #type_unknown