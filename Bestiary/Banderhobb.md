# Banderhobb

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Banderhobb | Monstrosity | 5 | 84 (8d10 + 40) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 5d6 + 5 | 15 | - |
| Tongue | 3d6 | 15 | - |
| Swallow | 3d6 | - | - |
| Shadow Step | - | - | - |


**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}22 ({@damage 5d6 + 5}) piercing damage, and the target is {@condition grappled} (escape {@dc 15}) if it is a Large or smaller creature. Until this grapple ends, the target is {@condition restrained}, and the banderhobb can't use its bite attack or tongue attack on another target.

**Tongue.** {@atk mw} {@hit 8} to hit, reach 15 ft., one target. {@h}10 ({@damage 3d6}) necrotic damage, and the target must make a {@dc 15} Strength saving throw. On a failed save, the target is pulled to a space within 5 feet of the banderhobb, which can use a bonus action to make a bite attack against the target.

**Swallow.** The banderhobb makes a bite attack against a Medium or smaller creature it is grappling. If the attack hits, the target is swallowed, and the grapple ends. The swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the banderhobb and it takes 10 ({@damage 3d6}) necrotic damage at the start of each of the banderhobb's turns. A creature reduced to 0 hit points in this way stops taking necrotic damage and becomes stable. The banderhobb can have only one target swallowed at a time. While the banderhobb isn't {@condition incapacitated}, it can regurgitate the creature at any time (no action required) in a space within 5 feet of it. The creature exits {@condition prone}. If the banderhobb dies, it likewise regurgitates a swallowed creature.

**Shadow Step.** The banderhobb magically teleports up to 30 feet to an unoccupied space of dim light or darkness that it can see. Before or after teleporting, it can make a bite or tongue attack.

^Tags: #monster #type_monstrosity