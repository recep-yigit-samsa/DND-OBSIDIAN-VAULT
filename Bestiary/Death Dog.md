# Death Dog

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Death Dog | Monstrosity | 1 | 39 (6d8 + 12) | 12 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d4 + 2 | 12 | - |


**Multiattack.** The death dog makes two Bite attacks.

**Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}4 ({@damage 1d4 + 2}) Piercing damage. If the target is a creature, it is subjected to the following effect. {@actSave con} {@dc 12}. {@actSaveFail 1} The target has the {@condition Poisoned|XPHB} condition. While {@condition Poisoned|XPHB}, the target's {@variantrule Hit Points|XPHB|Hit Point} maximum doesn't return to normal when finishing a {@variantrule Long Rest|XPHB}, and it repeats the save every 24 hours that elapse, ending the effect on itself on a success. Subsequent Failures: The {@condition Poisoned|XPHB} target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by 5 ({@dice 1d10}).

^Tags: #monster #type_monstrosity