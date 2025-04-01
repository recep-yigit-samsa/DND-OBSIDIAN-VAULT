# Gug

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gug | Giant | 12 | 230 (20d12 + 100) | 17 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Grasping Claw | 2d10 + 7 | 17 | - |
| Stomp | 2d12 + 7 | 17 | - |
| Fling | 1d6 | 17 | - |
| Swallow | 4d6 | 19 | - |


**Multiattack.** The gug makes two four Grasping Claw attacks, or it makes two Grasping Claw attacks and two Stomp attacks. It can replace one Grasping Claw attack with a use of Fling or Swallow.

**Grasping Claw.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}18 ({@damage 2d10 + 7}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 17}) if it is a Large or smaller creature. The gug has four Grasping Claws, each of which can grapple only one target.

**Stomp.** {@atk mw} {@hit 11} to hit, reach 10 ft. {@h}20 ({@damage 2d12 + 7}) bludgeoning damage, and the target must succeed on a {@dc 17} Strength saving throw or be knocked {@condition prone}.

**Fling.** One Large or smaller object held or creature {@condition grappled} by the gug is thrown up to 60 feet in a random direction and knocked {@condition prone}. If a thrown target strikes a solid surface, the target takes 3 ({@damage 1d6}) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a {@dc 17} Dexterity saving throw or take the same damage and be knocked {@condition prone}.

**Swallow.** The gug makes one Grasping Claw attack against a Large or smaller creature it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the gug, and it takes 14 ({@damage 4d6}) acid damage at the start of each of the gug's turns. A gug can have only one creature swallowed at a time. If the gug takes 30 damage or more on a single turn from the swallowed creature, the gug must succeed on a {@dc 19} Constitution saving throw at the end of that turn or regurgitate the creature, which falls {@condition prone} in a space within 10 feet of the gug. If the gug dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 10 feet of movement, exiting {@condition prone}.

^Tags: #monster #type_giant