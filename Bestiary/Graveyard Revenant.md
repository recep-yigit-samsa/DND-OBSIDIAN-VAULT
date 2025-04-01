# Graveyard Revenant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Graveyard Revenant | Undead | 7 | 161 (14d12 + 70) | 14 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Suffocate | 1d10 + 5 + 3d6 | 15 | - |
| Haunting Glare {@recharge 5} | - | 15 | - |


**Multiattack.** The revenant makes two Suffocate attacks.

**Suffocate.** {@atkr m} {@hit 8}, reach 10 ft. {@h}10 ({@damage 1d10 + 5}) Bludgeoning damage plus 10 ({@damage 3d6}) Necrotic damage. If the target is a Large or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 15}). Until the grapple ends, the target is suffocating. The revenant can have up to two targets {@condition Grappled|XPHB} in this way at a time.

**Haunting Glare {@recharge 5}.** {@actSave wis} {@dc 15}, each creature in a 30-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the revenant. {@actSaveFail} The target has the {@condition Paralyzed|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_undead