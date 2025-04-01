# Sandman

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sandman | Celestial | 5 | 82 (11d8 + 33) | 14 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d6 + 4 + 2d6 | - | - |
| Encourage Dreams {@recharge 5} | 10d6 | 15 | - |
| Dreamer's Sand {@recharge 5} | - | 15 | - |


**Multiattack.** The sandman makes two Claw attacks. It can replace one attack with a use of Dreamer's Sand, if available.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage plus 7 ({@damage 2d6}) psychic damage. Damage from this attack doesn't wake an {@condition unconscious} creature, unless the {@condition unconscious} creature is below half its hp maximum. If the sandman scores a critical hit, the target is cursed with the eye-closer's curse. While cursed, the creature is {@condition blinded} until it finishes a long rest or until the curse is lifted by remove curse or similar magic.

**Encourage Dreams {@recharge 5}.** The sandman encourages powerful dreams in the minds of up to three {@condition unconscious} creatures it can see within 30 feet of it. Each target must make a {@dc 15} Charisma saving throw. On a failure, nightmares fill the target's mind, and the target takes 35 ({@damage 10d6}) psychic damage, wakes from its sleep, and is {@condition frightened} for 1 minute. On a success, pleasant dreams fill the target's mind, and the target regains 10 {@dice 3d6} hp and can choose to remain {@condition unconscious} or awaken. A {@condition frightened} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Dreamer's Sand {@recharge 5}.** The sandman throws magical sand in a 30-foot cone. Each creature in that area must succeed on a {@dc 15} Constitution saving throw or fall {@condition unconscious} for 10 minutes. This effect ends for a creature if the creature takes damage or another creature uses an action to wake it.

^Tags: #monster #type_celestial