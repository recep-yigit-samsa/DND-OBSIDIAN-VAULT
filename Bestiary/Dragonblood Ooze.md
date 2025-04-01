# Dragonblood Ooze

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dragonblood Ooze | Ooze | 5 | 68 (8d10 + 24) | 14 | walk: 20 ft., climb: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pseudopod | 1d10 + 4 + 4d6 + 2d6 | 15 | - |
| Slime Breath {@recharge} | 4d10 | 14 | - |


**Multiattack.** The ooze makes two Pseudopod attacks. The ooze can replace one Pseudopod attack with its Slime Breath, if available.

**Pseudopod.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}9 ({@damage 1d10 + 4}) bludgeoning damage plus 14 ({@damage 4d6}) acid damage. If the target is a Large or smaller creature, it is {@condition grappled} (escape {@dc 15}). Until this grapple ends, the target takes 7 ({@damage 2d6}) acid damage at the start of each of its turns.

**Slime Breath {@recharge}.** The ooze expels a spray of its gelatinous mass in a 30-foot cone. Each creature in that area must make a {@dc 14} Dexterity saving throw. On a failed save, the creature takes 22 ({@damage 4d10}) acid damage and is pulled up to 30 feet straight toward the ooze. On a successful save, the creature takes half as much damage and isn't pulled.

^Tags: #monster #type_ooze