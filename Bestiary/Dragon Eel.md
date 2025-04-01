# Dragon Eel

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dragon Eel | Dragon | 12 | 195 (17d12 + 85) | 18 | walk: 20 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d8 + 8 + 1d10 | 18 | - |
| Tail Slap | 5d8 + 8 + 1d10 | 18 | - |
| Lightning Breath {@recharge} | 10d10 | 18 | - |


**Multiattack.** The dragon eel makes one Bite attack and one Tail Slap attack.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}26 ({@damage 4d8 + 8}) piercing damage plus 5 ({@damage 1d10}) lightning damage, and the target must succeed on a {@dc 18} Constitution saving throw or become {@condition paralyzed} for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Tail Slap.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}30 ({@damage 5d8 + 8}) bludgeoning damage plus 5 ({@damage 1d10}) lightning damage, and the target must succeed on a {@dc 18} Strength saving throw or be pushed up to 10 feet away from the eel. The dragon eel can choose to not push a target.

**Lightning Breath {@recharge}.** The dragon eel exhales lightning in a 60-foot line that is 5 feet wide. Each target in that line must make a {@dc 18} Dexterity saving throw, taking 55 ({@damage 10d10}) lightning damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon