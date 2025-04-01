# Maw of Yeenoghu

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Maw of Yeenoghu | Unknown | 10 | 161 (14d12 + 70) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 6 | - | - |
| Fang Fling | 1d10 + 6 | - | - |
| Gorging Charge {@recharge 5} | 3d12 + 6 | 18 | - |


**Multiattack.** The maw makes two Bite or Fang Fling attacks.

**Bite.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}19 ({@damage 2d12 + 6}) piercing damage.

**Fang Fling.** {@atk rw} {@hit 10} to hit, range 30/90 ft., one target. {@h}11 ({@damage 1d10 + 6}) piercing damage.

**Gorging Charge {@recharge 5}.** The maw moves up to its speed without provoking opportunity attacks and can move through the spaces of Large or smaller creatures. Each time the maw enters a creature's space for the first time during this move, that creature must succeed on a {@dc 18} Strength saving throw or take 25 ({@damage 3d12 + 6}) piercing damage and have the {@condition grappled} condition (escape {@dc 16}); if a creature is already {@condition grappled} this way, it has the {@condition prone} condition. Until this grapple ends, the target has the {@condition restrained} condition. The maw can have only one creature {@condition grappled} in this way at a time.

^Tags: #monster #type_unknown