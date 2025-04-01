# Space Eel

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Space Eel | Beast | 1/2 | 7 (2d6) | 14 | walk: 10 ft., fly: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 1 + 1d6 + 1 | - | - |
| Tail Spine | 1d4 + 1 | 10 | - |


**Multiattack.** If it isn't attached to a creature, the eel makes one Bite attack and one Tail Spine attack.

**Bite.** {@atk mw} {@hit 3} to hit, reach 5 ft., one creature. {@h}4 ({@damage 1d6 + 1}) piercing damage, and the eel attaches to the target. While attached, the eel can't make Bite attacks. Instead, the target takes 4 ({@damage 1d6 + 1}) piercing damage at the start of each of the eel's turns. The eel can detach itself as a bonus action. A creature, including the target, can use its action to detach the eel.

**Tail Spine.** {@atk mw} {@hit 3} to hit, reach 5 ft., one creature. {@h}3 ({@damage 1d4 + 1}) piercing damage, and the target must succeed on a {@dc 10} Constitution saving throw or be {@condition poisoned} for 1 minute. Until this poison ends, the target is {@condition paralyzed}. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_beast