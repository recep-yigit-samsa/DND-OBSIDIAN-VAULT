# Tosculi Warrior

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tosculi Warrior | Unknown | 3 | 58 (9d6 + 27) | 15 | walk: 20 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d4 + 5 | - | - |
| Stinger | 2d4 + 5 | 13 | - |
| Prepare Host | - | 13 | - |


**Multiattack.** The tosculi warrior makes one Claw attack and one Stinger attack.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d4 + 5}) slashing damage.

**Stinger.** {@atk mw} {@hit 7} to hit, reach 5 ft., one creature. {@h}10 ({@damage 2d4 + 5}) piercing damage, and the target must succeed on a {@dc 13} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned} in this way, the target is also {@condition paralyzed}. A {@condition poisoned} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Prepare Host.** The tosculi extends the paralysis on a creature within 5 feet of it that was {@condition paralyzed} by a tosculi's Stinger attack. The {@condition paralyzed} target must succeed on a {@dc 13} Constitution saving throw or be {@condition paralyzed} for 8 hours and no longer makes saving throws to end the paralysis. The paralysis ends if the target takes damage while below half its hp maximum. Otherwise, a spell or effect that cures disease ends this paralysis.

^Tags: #monster #type_unknown