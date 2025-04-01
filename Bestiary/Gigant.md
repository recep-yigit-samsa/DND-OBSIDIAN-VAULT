# Gigant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gigant | Monstrosity | 20 | 325 (21d20 + 105) | 17 | walk: 50 ft., burrow: 50 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Mandibles | 4d6 + 7 + 4d6 + 7 | 17 | - |
| Talons | 3d6 + 7 | - | - |
| Scale Dust {@recharge 5} | 10d8 | 19 | - |


**Multiattack.** The gigant makes one Mandibles attack and two Talons attacks.

**Mandibles.** {@atk mw} {@hit 13} to hit, reach 10 ft., one creature. {@h}21 ({@damage 4d6 + 7}) slashing damage, and the target has the {@condition grappled} condition (escape {@dc 17}). Until the grapple ends, the target takes 21 ({@damage 4d6 + 7}) slashing damage at the start of each of the gigant's turns. While the gigant is grappling a target, it can't use Mandibles against other targets.

**Talons.** {@atk mw} {@hit 13} to hit, reach 20 ft., one target. {@h}17 ({@damage 3d6 + 7}) slashing damage, and the target is pulled 10 feet straight toward the gigant.

**Scale Dust {@recharge 5}.** The gigant releases magical dust from its wings in a 30-foot cube. Each creature in that area must make a {@dc 19} Constitution saving throw, taking 45 ({@damage 10d8}) poison damage on a failed save, or half as much damage on a successful one. On a success or failure, the creature has the {@condition poisoned} condition for 1 hour. While {@condition poisoned} this way, the creature can't regain hit points.

^Tags: #monster #type_monstrosity