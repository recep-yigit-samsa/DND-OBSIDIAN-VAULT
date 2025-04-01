# Night Scorpion

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Night Scorpion | Beast | 3 | 90 (12d10 + 24) | 14 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d8 + 2 | 12 | - |
| Sting | 1d10 + 2 + 2d6 | 12 | - |


**Multiattack.** The scorpion makes two Claw attacks and one Sting attack.

**Claw.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature. {@h}6 ({@damage 1d8 + 2}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 12}). The scorpion has two claws, each of which can grapple only one target.

**Sting.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature. {@h}7 ({@damage 1d10 + 2}) piercing damage, and the target must make a {@dc 12} Constitution saving throw. On a failure, the target takes 7 ({@damage 2d6}) poison damage and is {@condition blinded} for 1 hour. On a success, a creature takes half the damage and isn't {@condition blinded}. If the target fails the saving throw by 5 or more, it is also {@condition poisoned} for 1 minute, and it is {@condition paralyzed} while {@condition poisoned} in this way. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_beast