# Hraesvelgr

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hraesvelgr | Unknown | 19 | 241 (21d12 + 105) | 19 | walk: {'number': 50, 'condition': '(20 ft. fly 120 ft. in roc form)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 19 | - |
| Beak (Roc Form Only) | 4d8 + 7 | - | - |
| Fist (Giant Form Only) | 3d8 + 7 | - | - |
| Talons (Roc Form Only) | 3d6 + 7 | 17 | - |
| Gale Blast | 2d8 + 5 + 2d6 | - | - |
| Swallow (Roc Form Only) | 5d6 | 15 | - |
| Sudden Gust {@recharge 5} | 18d6 | 19 | - |


**Multiattack.** Hraesvelgr makes one Beak attack and two Talon attacks, or he makes three Fist attacks. Alternatively, he can make three Gale Blast attacks. If two Fist attacks hit one creature, the target must succeed on a {@dc 19} Constitution saving throw or be {@condition stunned} until the end of its next turn.

**Beak (Roc Form Only).** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}25 ({@damage 4d8 + 7}) piercing damage.

**Fist (Giant Form Only).** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}20 ({@damage 3d8 + 7}) bludgeoning damage.

**Talons (Roc Form Only).** {@atk mw} {@hit 13} to hit, reach 5 ft., one target. {@h}17 ({@damage 3d6 + 7}) slashing damage, and the target is {@condition grappled} (escape {@dc 17}). Until this grapple ends, the target is {@condition restrained}. Hraesvelgr has two talons, each of which can grapple only one target.

**Gale Blast.** {@atk rs} {@hit 11} to hit, range 120 ft., one target. {@h}14 ({@damage 2d8 + 5}) bludgeoning damage plus 7 ({@damage 2d6}) cold damage.

**Swallow (Roc Form Only).** Hraesvelgr makes one Beak attack against a Large or smaller creature he is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside Hraesvelgr, and it takes 17 ({@damage 5d6}) acid damage at the start of each of Hraesvelgr's turns. Hraesvelgr can have only one creature swallowed at a time. If Hraesvelgr takes 40 damage or more on a single turn from the swallowed creature, Hraesvelgr must succeed on a {@dc 15} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 10 feet of Hraesvelgr. Hraesvelgr has disadvantage on this saving throw if he isn't in his roc form. If Hraesvelgr dies, a swallowed creature is no longer {@condition restrained} by him and can escape from the corpse by using 15 feet of movement, exiting {@condition prone}.

**Sudden Gust {@recharge 5}.** Hraesvelgr unleashes a powerful gust of wind in a 60-foot line that is 10 feet wide. Each creature in the line must make a {@dc 19} Strength saving throw. On a failure, a creature takes 63 ({@damage 18d6}) bludgeoning damage and is pushed up to 15 feet away from Hraesvelgr. On a success, a creature takes half the damage and isn't pushed.

^Tags: #monster #type_unknown