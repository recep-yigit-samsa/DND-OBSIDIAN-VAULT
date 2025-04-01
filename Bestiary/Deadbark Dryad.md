# Deadbark Dryad

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Deadbark Dryad | Fey | 13 | 187 (22d8 + 88) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Poisonous Thorn | 4d4 + 3 + 3d6 | 17 | - |
| Sapping Vine | 3d8 | 16 | No Damage ❌ |


**Multiattack.** The dryad makes two Poisonous Thorn attacks and one Sapping Vine attack.

**Poisonous Thorn.** {@atk mw,rw} {@hit 8} to hit, reach 5 ft. or range 120 ft., one target. {@h}13 ({@damage 4d4 + 3}) piercing damage plus 10 ({@damage 3d6}) poison damage. If the target is a creature, it must succeed on a {@dc 17} Constitution saving throw or have the {@condition poisoned} condition until the start of the dryad's next turn.

**Sapping Vine.** {@atk mw} {@hit 8} to hit, reach 30 ft., one target. {@h}The target has the {@condition grappled} condition (escape {@dc 16}). Until the grapple ends, the target has the {@condition restrained} condition, and the dryad can't use the same vine on another target. A creature {@condition restrained} in this way takes 13 ({@damage 3d8}) necrotic damage at the start of its turn. The dryad has six vines. Each vine can be attacked (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying a vine deals no damage to the dryad, but any creature {@condition grappled} by that vine no longer has the {@condition grappled} condition. All vines immediately wither and disappear when the dryad is reduced to 0 hit points.

^Tags: #monster #type_fey