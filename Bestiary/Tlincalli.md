# Tlincalli

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tlincalli | Monstrosity | 5 | 85 (10d10 + 30) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Longsword | 1d8 + 3 + 1d10 + 3 | - | - |
| Spiked Chain | 1d6 + 3 | 11 | - |
| Sting | 1d6 + 3 + 4d6 | 14 | - |


**Multiattack.** The tlincalli makes two attacks: one with its longsword or spiked chain, and one with its sting.

**Longsword.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) slashing damage, or 8 ({@damage 1d10 + 3}) slashing damage if used with two hands.

**Spiked Chain.** {@atk mw} {@hit 6} to hit, reach 10 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage, and the target is {@condition grappled} (escape {@dc 11}) if it is a Large or smaller creature. Until this grapple ends, the target is {@condition restrained}, and the tlincalli can't use the spiked chain against another target.

**Sting.** {@atk mw} {@hit 6} to hit, reach 5 ft., one creature. {@h}6 ({@damage 1d6 + 3}) piercing damage plus 14 ({@damage 4d6}) poison damage, and the target must succeed on a {@dc 14} Constitution saving throw or be {@condition poisoned} for 1 minute. If it fails the saving throw by 5 or more, the target is also {@condition paralyzed} while {@condition poisoned}. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_monstrosity