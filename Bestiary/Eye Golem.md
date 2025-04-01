# Eye Golem

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Eye Golem | Construct | 11 | 157 (15d10 + 75) | 20 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d10 + 6 + 4d8 | - | - |
| Gaze of Ancient Light {@recharge 5} | 10d6 | 17 | - |
| Primal Voice of Doom | - | 17 | - |


**Multiattack.** The eye golem can use its Primal Voice of Doom. It then makes two Slam attacks.

**Slam.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}17 ({@damage 2d10 + 6}) bludgeoning damage plus 18 ({@damage 4d8}) radiant damage.

**Gaze of Ancient Light {@recharge 5}.** The golem opens all of its eyes and emits a burst of blinding light. Each creature within 30 feet of it must make a {@dc 17} Dexterity saving throw. On a failure, a creature takes 35 ({@damage 10d6}) radiant damage and is {@condition blinded} for 1 minute. On a success, a creature takes half the damage and isn't {@condition blinded}. A creature that fails the saving throw by 5 or more is also {@condition stunned} until the end of its next turn. A {@condition blinded} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Primal Voice of Doom.** The golem intones a disturbing invocation of the sun god at one creature it can see within 30 feet of it. The target must succeed on a {@dc 17} Wisdom saving throw or be {@condition frightened} for 1 minute. The {@condition frightened} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_construct