# Crimson Drake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Crimson Drake | Dragon | 1 | 45 (10d4 + 20) | 14 | walk: 15 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 2 + 1d6 | - | - |
| Stinger | 1d4 + 2 + 1d4 | 12 | - |
| Fire Breath {@recharge} | 3d6 | 12 | - |


**Multiattack.** The crimson drake makes one Bite attack and one Stinger attack.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage plus 3 ({@damage 1d6}) fire damage.

**Stinger.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d4 + 2}) piercing damage, and the target must succeed on a {@dc 12} Constitution saving throw or become {@condition poisoned} for 1 minute. If the saving throw fails by 5 or more, the target takes 2 ({@damage 1d4}) poison damage at the start of each of its turns while {@condition poisoned}. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Fire Breath {@recharge}.** The drake exhales fire in a 15-foot cone. Each creature in that area must make a {@dc 12} Dexterity saving throw, taking 10 ({@damage 3d6}) fire damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon