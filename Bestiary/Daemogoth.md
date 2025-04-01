# Daemogoth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Daemogoth | Fiend | 10 | 157 (15d12 + 60) | 16 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Agonizing Burst | 2d10 | - | - |
| Terrify {@recharge 4} | 6d10 | 17 | - |


**Multiattack.** The daemogoth makes three Agonizing Burst attacks. It can use Terrify, if available, in place of one of the attacks.

**Agonizing Burst.** {@atk ms,rs} {@hit 9} to hit, reach 10 ft. or range 120 ft., one target. {@h}11 ({@damage 2d10}) force damage. If the target is a creature, the daemogoth regains 5 hit points.

**Terrify {@recharge 4}.** The daemogoth targets one creature it can see within 120 feet of itself. The target must make a {@dc 17} Wisdom saving throw. On a failed save, the target takes 33 ({@damage 6d10}) psychic damage and is {@condition frightened} of the daemogoth until the end of the daemogoth's next turn, and the daemogoth regains 5 hit points. On a successful save, the target takes half as much damage and isn't {@condition frightened}, and the daemogoth doesn't heal.

^Tags: #monster #type_fiend