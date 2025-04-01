# Clockwork Oaken Bolter

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Clockwork Oaken Bolter | Construct | 5 | 117 (18d8 + 36) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Lancing Bolt | 2d10 + 4 | - | - |
| Harpoon | 1d10 + 4 + 1d10 | 12 | - |
| Explosive Bolt {@recharge 5} | 5d6 | 15 | - |


**Multiattack.** The clockwork makes two Lancing Bolt attacks or one Lancing Bolt attack and one Harpoon attack.

**Lancing Bolt.** {@atk mw,rw} {@hit 7} to hit, reach 5 ft. or range 100/400 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage.

**Harpoon.** {@atk rw} {@hit 7} to hit, range 50/200 ft., one target. {@h}9 ({@damage 1d10 + 4}) piercing damage, and the target is {@condition grappled} (escape {@dc 12}). While {@condition grappled} in this way, a creature's speed isn't reduced, but it can move only in directions that bring it closer to the clockwork. A creature takes 5 ({@damage 1d10}) slashing damage if it escapes from the grapple or if it tries and fails. The clockwork can grapple only one creature at a time with its harpoon.

**Explosive Bolt {@recharge 5}.** The clockwork launches an explosive charge at a point within 120 feet. Each creature in a 20-foot-radius sphere centered on that point must make a {@dc 15} Dexterity saving throw, taking 17 ({@damage 5d6}) fire damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct