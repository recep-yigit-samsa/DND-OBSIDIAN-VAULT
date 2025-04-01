# Dragonbone Golem

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dragonbone Golem | Construct | 11 | 161 (19d10 + 57) | 17 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pinion | 2d6 + 5 | 17 | - |
| Rend | 2d6 + 5 + 1d10 | - | - |
| Petrifying Breath {@recharge 5} | 10d6 | 15 | - |


**Multiattack.** The golem makes one Pinion attack and two Rend attacks.

**Pinion.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage. If the target is a Medium or smaller creature, it is pinned beneath the bony pinion and {@condition restrained}. The golem has two pinions, each of which can restrain one target. If a creature is {@condition restrained} by one of the pinions, the golem can't attack with it. Any creature {@condition restrained} by a pinion can free itself at the start of its turn with a successful {@dc 17} Strength ({@skill Athletics}) check.

**Rend.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage plus 5 ({@damage 1d10}) necrotic damage.

**Petrifying Breath {@recharge 5}.** The golem emits a 60-foot cone of petrifying gas from its mouth. Each creature in that area must succeed on a {@dc 15} Constitution saving throw or take 35 ({@damage 10d6}) poison damage and be {@condition restrained} as it begins to turn to stone. The {@condition restrained} target must repeat the saving throw at the end of its next turn. On a successful save, the effect ends on the target. On a failed save, the target is {@condition petrified}.

^Tags: #monster #type_construct