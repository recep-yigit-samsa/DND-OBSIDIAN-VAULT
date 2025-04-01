# Corpse Mound

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Corpse Mound | Undead | 11 | 207 (18d12 + 90) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d10 + 7 + 3d6 | 17 | - |
| Bone Shard | 2d6 + 7 + 3d6 | 17 | - |
| Envelop | 2d10 + 7 + 3d6 | 17 | - |


**Multiattack.** The corpse mound makes two Slam or Bone Shard attacks. If both Slam attacks hit a Large or smaller target, the corpse mound can immediately use Envelop on it.

**Slam.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}18 ({@damage 2d10 + 7}) bludgeoning damage plus 10 ({@damage 3d6}) necrotic damage, and the target is {@condition grappled} (escape {@dc 17}). Until this grapple ends, the target is {@condition restrained}.

**Bone Shard.** {@atk rw} {@hit 11} to hit, range 30/120 ft., one target. {@h}14 ({@damage 2d6 + 7}) piercing damage plus 10 ({@damage 3d6}) necrotic damage, and the target must succeed on a {@dc 17} Strength saving throw or be knocked {@condition prone} and {@condition restrained} as it is pinned to the ground by the shard. A creature, including the {@condition restrained} target, can take its action to free the target by succeeding on a {@dc 17} Strength check.

**Envelop.** The corpse mound envelops a Large or smaller creature within 5 feet of it that is {@condition restrained} by its Bone Shard or a Large or smaller creature {@condition grappled} by it. The enveloped target is {@condition blinded}, {@condition restrained}, and unable to breathe, and it must succeed on a {@dc 17} Strength saving throw at the start of each of the mound's turns or take 18 ({@damage 2d10 + 7}) bludgeoning damage. If the mound moves, the enveloped target moves with it. The mound can have no more than four creatures enveloped at a time. A creature within 5 feet of the mound, including the enveloped creature, can free the enveloped creature by succeeding on a {@dc 17} Strength check. Any creature that makes such an attempt takes 10 ({@damage 3d6}) necrotic damage.

^Tags: #monster #type_undead