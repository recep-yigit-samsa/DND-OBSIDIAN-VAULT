# Hollow Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Hollow Dragon | Undead | 18 | 241 (21d12 + 105) | 19 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 6 + 2d8 | - | - |
| Claw | 2d6 + 6 | - | - |
| Sapping Presence | - | 19 | - |
| Radiant Breath {@recharge 5} | 12d8 | 19 | - |


**Multiattack.** The hollow dragon makes one Bite attack and two Claw attacks, and it can use Sapping Presence.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage plus 9 ({@damage 2d8}) radiant damage.

**Claw.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage.

**Sapping Presence.** Each creature of the hollow dragon's choice within 60 feet of it must make a {@dc 19} Wisdom saving throw. On a failed save, the creature's speed is halved and it has disadvantage on attack rolls until the end of its next turn. On a successful save, the creature is immune to this hollow dragon's Sapping Presence for 24 hours.

**Radiant Breath {@recharge 5}.** The hollow dragon exhales radiant flames in a 60-foot cone. Each creature in that area must make a {@dc 19} Dexterity saving throw, taking 54 ({@damage 12d8}) radiant damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_undead