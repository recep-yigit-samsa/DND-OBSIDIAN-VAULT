# Blue Slaad

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Blue Slaad | Aberration | 7 | 133 (14d10 + 56) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Mutating Claw | 2d6 + 5 + 1d6 | 15 | - |


**Multiattack.** The slaad makes three Mutating Claw attacks.

**Mutating Claw.** {@atkr m} {@hit 8}, reach 10 ft. {@h}12 ({@damage 2d6 + 5}) Slashing damage plus 3 ({@damage 1d6}) Poison damage. If the target is a Humanoid not cursed by a slaad, it is subjected to the following effect. {@actSave con} {@dc 15}. {@actSaveFail} The target is cursed. The cursed target can't regain {@variantrule Hit Points|XPHB}, and its {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by 10 ({@dice 3d6}) after every 24 hours and doesn't return to normal after finishing a {@variantrule Long Rest|XPHB}. If the curse reduces the target's {@variantrule Hit Points|XPHB|Hit Point} maximum to 0, the curse ends, and instead of dying, the target instantly transforms into a {@creature Red Slaad|XMM} or, if it can cast spells of level 3 or higher, a {@creature Green Slaad|XMM}. Only a {@spell Wish|XPHB} spell can reverse this transformation.

^Tags: #monster #type_aberration