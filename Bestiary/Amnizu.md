# Amnizu

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Amnizu | Unknown | 18 | 202 (27d8 + 81) | 21 | walk: 30 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Taskmaster Whip | 2d4 + 5 + 6d10 | - | - |
| Disruptive Touch | 8d10 | - | - |
| Poison Mind | 4d12 | 19 | - |
| Forgetfulness {@recharge} | - | 18 | - |


**Multiattack.** The amnizu uses Poison Mind. It also makes two attacks: one with its whip and one with its Disruptive Touch.

**Taskmaster Whip.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}10 ({@damage 2d4 + 5}) slashing damage plus 33 ({@damage 6d10}) force damage.

**Disruptive Touch.** {@atk ms} {@hit 11} to hit, reach 5 ft., one target. {@h}44 ({@damage 8d10}) necrotic damage.

**Poison Mind.** The amnizu targets one or two creatures that it can see within 60 feet of it. Each target must succeed on a {@dc 19} Wisdom saving throw or take 26 ({@damage 4d12}) necrotic damage and is {@condition blinded} until the start of the amnizu's next turn.

**Forgetfulness {@recharge}.** The amnizu targets one creature it can see within 60 feet of it. That creature must make a {@dc 18} Intelligence saving throw and on a failure the target is {@condition stunned} for 1 minute. A {@condition stunned} creature repeats the saving throw at the end of each of its turns, ending the effect on itself on a success. If the target remains {@condition stunned} for the full minute, it forgets everything it sensed, experienced, and learned during the last 5 hours.

^Tags: #monster #type_unknown