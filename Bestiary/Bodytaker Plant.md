# Bodytaker Plant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bodytaker Plant | Plant | 7 | 92 (8d12 + 40) | 16 | walk: 10 ft., climb: 10 ft., swim: 10 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Vine Lash | 2d6 + 4 | 15 | - |
| Entrapping Pod | 4d8 + 4 | 16 | - |


**Multiattack.** The plant makes three Vine Lash attacks.

**Vine Lash.** {@atk mw} {@hit 7} to hit, reach 20 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage. If the target is a creature, it is {@condition grappled} (escape {@dc 15}). Until the grapple ends, the target is {@condition restrained}. The plant has four vines, each of which can grapple one target.

**Entrapping Pod.** {@atk mw} {@hit 7} to hit, reach 5 ft., one Medium or smaller creature {@condition grappled} by the plant. {@h}22 ({@damage 4d8 + 4}) acid damage, and the target is pulled into the plant's space and enveloped by the pod, and the grapple ends. While enveloped, the target is {@condition restrained}, and it has {@quickref Cover||3||total cover} against attacks and effects originating outside the pod. The enveloped target must also immediately succeed on a {@dc 16} Constitution saving throw or be {@condition stunned} by the plant's sapping enzymes until it is removed from the pod or the plant dies. The enveloped target doesn't require air and gains 1 level of {@condition exhaustion} for each hour it spends in the pod. If the target dies while enveloped, it immediately emerges from the pod as a living podling, wearing or carrying all of the original creature's equipment. As an action, a creature within 5 feet of the bodytaker plant that is outside the pod can open the pod and pull the target free with a successful {@dc 15} Strength check. If the plant dies, the target is no longer {@condition restrained} and can escape from the pod by spending 10 feet of movement, exiting {@condition prone}. The plant has one pod, which can envelop one creature at a time.

^Tags: #monster #type_plant