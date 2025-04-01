# Arasta

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Arasta | Monstrosity | 21 | 300 (24d12 + 144) | 19 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d8 + 7 + 5d12 | 21 | - |
| Claws | 3d6 + 7 | - | - |
| Web of Hair {@recharge 4} | - | 21 | - |


**Multiattack.** Arasta makes three attacks: one with her bite and two with her claws.

**Bite.** {@atk mw} {@hit 14} to hit, reach 5 ft., one creature. {@h}20 ({@damage 3d8 + 7}) piercing damage, and the target must make a {@dc 21} Constitution saving throw, taking 32 ({@damage 5d12}) poison damage on a failed save, or half as much damage on a successful one. If the damage reduces the target to 0 hit points, the target is stable but {@condition poisoned} for 1 hour, even after regaining hit points, and is {@condition paralyzed} while {@condition poisoned} in this way.

**Claws.** {@atk mw} {@hit 14} to hit, reach 5 ft., one target. {@h}17 ({@damage 3d6 + 7}) slashing damage.

**Web of Hair {@recharge 4}.** Arasta unleashes her hair in the form of webbing that fills a 30-foot cube next to her. The web is {@quickref difficult terrain||3}, its area is lightly obscured, and it lasts for 1 minute. Any creature that moves into the web or that starts its turn there must make a {@dc 21} Dexterity saving throw. On a failed save, the creature is {@condition restrained} while in the web. A creature can use an action to make a {@dc 21} Strength check. On a success, it can free itself or a creature within 5 feet of it that is {@condition restrained} by the web. This webbing is immune to all damage except magical fire. A 5-foot cube of the web is destroyed if it takes at least 20 fire damage from a spell or other magical source on a single turn.

^Tags: #monster #type_monstrosity