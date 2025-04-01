# Demonfeed Spider

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Demonfeed Spider | Fiend | 8 | 75 (10d10 + 20) | 16 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d10 + 3 + 6d8 | 14 | - |
| Stinger | 1d12 + 3 | 14 | - |
| Web Spinner | - | 14 | - |


**Multiattack.** The spider makes two melee attacks: one with its bite and one with its stinger; or the spider can make one attack with its web spinner followed by a melee attack.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d10 + 3}) piercing damage, and the target must make a {@dc 14} Constitution {@quickref saving throws|PHB|2|1|saving throw}. On a failed save, the target takes 27 ({@damage 6d8}) poison damage and is {@condition poisoned} for 1 minute. On a successful save, the target takes half as much damage and isn't {@condition poisoned}. If this poison damage reduces the target to 0 hit points, the target is stable but {@condition poisoned} for 1 hour, even after regaining hit points, and is {@condition paralyzed} while {@condition poisoned} in this way.

**Stinger.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d12 + 3}) piercing damage, and the target must succeed on a {@dc 14} Constitution {@quickref saving throws|PHB|2|1|saving throw} or be {@condition paralyzed} for 1 minute. The target can repeat the {@quickref saving throws|PHB|2|1|saving throw} at the end of each of its turns, ending the effect on itself on a success.

**Web Spinner.** {@atk rw} {@hit 7} to hit, reach 40 ft., one target. {@h} The target is pulled 40 feet toward the spider and is {@condition grappled} (escape {@dc 14}). The spider can {@action grapple} only one creature at a time in this way. As an action, the spider can cocoon a creature it has {@condition grappled} in webbing, causing it to be {@condition restrained} and ending the {@condition grappled} condition.

^Tags: #monster #type_fiend