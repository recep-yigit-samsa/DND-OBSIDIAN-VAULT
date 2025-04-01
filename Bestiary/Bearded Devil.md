# Bearded Devil

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bearded Devil | Unknown | 3 | 58 (9d8 + 18) | 13 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Beard | 1d8 + 3 | - | - |
| Infernal Glaive | 1d10 + 3 | 12 | - |


**Multiattack.** The devil makes one Beard attack and one Infernal Glaive attack.

**Beard.** {@atkr m} {@hit 5}, reach 5 ft. {@h}7 ({@damage 1d8 + 3}) Piercing damage, and the target has the {@condition Poisoned|XPHB} condition until the start of the devil's next turn. Until this poison ends, the target can't regain {@variantrule Hit Points|XPHB}.

**Infernal Glaive.** {@atkr m} {@hit 5}, reach 10 ft. {@h}8 ({@damage 1d10 + 3}) Slashing damage. If the target is a creature and doesn't already have an infernal wound, it is subjected to the following effect. {@actSave con} {@dc 12}. {@actSaveFail} The target receives an infernal wound. While wounded, the target loses 5 ({@dice 1d10}) {@variantrule Hit Points|XPHB} at the start of each of its turns. The wound closes after 1 minute, after a spell restores {@variantrule Hit Points|XPHB} to the target, or after the target or a creature within 5 feet of it takes an action to stanch the wound, doing so by succeeding on a {@dc 12} Wisdom ({@skill Medicine|XPHB}) check.

^Tags: #monster #type_unknown