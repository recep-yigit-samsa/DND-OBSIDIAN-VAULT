# Coral Drake

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Coral Drake | Dragon | 7 | 127 (15d8 + 60) | 16 | walk: 15 ft., swim: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 4 | - | - |
| Spined Fin | 2d8 + 4 | - | - |
| Stinger | 2d6 + 4 + 2d4 | 15 | - |
| Biting Breath {@recharge 5} | 6d6 | 15 | - |


**Multiattack.** The coral drake makes one Bite attack and two Spined Fin attacks. It can replace its Bite attack with a Stinger attack.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage.

**Spined Fin.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage.

**Stinger.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage, and the target must succeed on a {@dc 15} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned}, the target takes 5 ({@damage 2d4}) poison damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Biting Breath {@recharge 5}.** The coral drake pressurizes the throat sacs that contain its growing young and spews tiny, ravenous hatchling drakes in a 15-foot cone. Each creature in the area must make a {@dc 15} Dexterity saving throw. On a failure, a creature takes 21 ({@damage 6d6}) piercing damage and is {@condition blinded} for 1 minute. On a success, a creature takes half the damage and isn't {@condition blinded}. A {@condition blinded} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_dragon