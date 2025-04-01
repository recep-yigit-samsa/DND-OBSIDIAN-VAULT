# Oaken Bolter

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Oaken Bolter | Construct | 5 | 58 (9d8 + 18) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Lancing Bolt | 2d10 + 4 | - | - |
| Harpoon | 1d10 + 4 + 1d10 | 12 | - |
| Explosive Bolt {@recharge 5} | 5d6 | 15 | - |


**Multiattack.** The oaken bolter makes two lancing bolt attacks or one lancing bolt attack and one harpoon attack.

**Lancing Bolt.** {@atk mw,rw} {@hit 7} to hit, reach 5 ft. or range 100/400 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage.

**Harpoon.** {@atk rw} {@hit 7} to hit, range 50/200 ft., one target. {@h}9 ({@damage 1d10 + 4}) piercing damage, and the target is {@condition grappled} (escape {@dc 12}). While {@condition grappled} in this way, a creature's speed isn't reduced, but it can move only in directions that bring it closer to the oaken bolter. A creature takes 5 ({@damage 1d10}) slashing damage if it escapes from the grapple or if it tries and fails. As a bonus action, the oaken bolter can pull a creature {@condition grappled} by it 20 feet closer. The oaken bolter can grapple only one creature at a time.

**Explosive Bolt {@recharge 5}.** The oaken bolter launches an explosive charge at a point within 120 feet. Each creature within 20 feet of that point must make a {@dc 15} Dexterity saving throw, taking 17 ({@damage 5d6}) fire damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct