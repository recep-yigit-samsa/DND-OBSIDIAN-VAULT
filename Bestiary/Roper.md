# Roper

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Roper | Aberration | 5 | 93 (11d10 + 33) | 20 | walk: 10 ft., climb: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 4 | - | - |
| Tentacle | - | 14 | No Damage ❌ |
| Reel | - | - | - |


**Multiattack.** The roper makes two Tentacle attacks, uses Reel, and makes two Bite attacks.

**Bite.** {@atkr m} {@hit 7}, reach 5 ft. {@h}17 ({@damage 3d8 + 4}) Piercing damage.

**Tentacle.** {@atkr m} {@hit 7}, reach 60 ft. {@h}The target has the {@condition Grappled|XPHB} condition (escape {@dc 14}) from one of six tentacles, and the target has the {@condition Poisoned|XPHB} condition until the grapple ends. The tentacle can be damaged, freeing a creature it has {@condition Grappled|XPHB} when destroyed (AC 20, HP 10, {@variantrule Immunity|XPHB} to Poison and Psychic damage). Damaging the tentacle deals no damage to the roper, and a destroyed tentacle regrows at the start of the roper's next turn.

**Reel.** The roper pulls each creature {@condition Grappled|XPHB} by it up to 30 feet straight toward it.

^Tags: #monster #type_aberration