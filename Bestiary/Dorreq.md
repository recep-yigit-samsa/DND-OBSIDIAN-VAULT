# Dorreq

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dorreq | Aberration | 4 | 93 (17d8 + 17) | 15 | walk: 20 ft., climb: 15 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 4 | - | - |
| Tentacles | 1d8 + 4 | 14 | - |
| Void Thrum {@recharge 5} | 3d6 + 3d6 | 14 | - |


**Multiattack.** The dorreq makes one Bite attack and two Tentacles attacks.

**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage.

**Tentacles.** {@atk mw} {@hit 6} to hit, reach 10 ft., one target. {@h}8 ({@damage 1d8 + 4}) bludgeoning damage, and if the target is a Medium or smaller creature, it is {@condition grappled} (escape {@dc 14}) and pulled up to 5 feet closer to the dorreq. Until this grapple ends, the target is {@condition restrained}. The dorreq can grapple up to two creatures at a time.

**Void Thrum {@recharge 5}.** The dorreq emits a barely audible, vibrating thrum laced with Void energy. Each creature within 20 feet of the dorreq must make a {@dc 14} Constitution saving throw, taking 10 ({@damage 3d6}) thunder damage and 10 ({@damage 3d6}) necrotic damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_aberration