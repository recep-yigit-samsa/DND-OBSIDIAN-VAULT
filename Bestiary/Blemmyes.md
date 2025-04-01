# Blemmyes

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Blemmyes | Monstrosity | 8 | 168 (16d10 + 80) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d6 + 5 + 4d6 | 15 | - |
| Slam | 2d8 + 5 | 16 | - |
| Rock | 4d10 + 5 | 16 | - |


**Multiattack.** The blemmyes makes one Bite attack and two Slam attacks.

**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}19 ({@damage 4d6 + 5}) piercing damage. If the target is {@condition incapacitated} and a Medium or smaller creature, the target is swallowed. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the blemmyes, and it takes 14 ({@damage 4d6}) acid damage at the start of each of the blemmyes' turns. The blemmyes can have only one target swallowed at a time. If the blemmyes takes 20 damage or more on a single turn from the swallowed creature, the blemmyes must succeed on a {@dc 15} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 5 feet of the blemmyes. If the blemmyes dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 5 feet of movement, exiting {@condition prone}.

**Slam.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d8 + 5}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 16} Wisdom saving throw or be {@condition stunned} until the end of its next turn.

**Rock.** {@atk rw} {@hit 8} to hit, range 30/120 ft., one target. {@h}27 ({@damage 4d10 + 5}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 16} Wisdom saving throw or be {@condition frightened} until the end of its next turn.

^Tags: #monster #type_monstrosity