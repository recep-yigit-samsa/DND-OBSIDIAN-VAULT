# Crimson Countess

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Crimson Countess | Monstrosity | 8 | 130 (20d8 + 40) | 17 | walk: 20 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Talons | 1d10 + 5 | - | - |
| Frightful Screech | - | 15 | - |
| Javelin | 1d6 + 5 + 4d6 | - | - |
| Thunder Blast {@recharge 5} | 4d6 | 15 | - |


**Multiattack.** The Crimson Countess can use her Frightful Screech. She then makes two attacks with her talons or one with her javelin.

**Talons.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}11 ({@damage 1d10 + 5}) slashing damage.

**Frightful Screech.** Each creature of the Crimson Countess' choice that is within 120 feet of her and not {@condition deafened} must succeed on a {@dc 15} Wisdom saving throw or become {@condition frightened} for 1 minute. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the effects of the Crimson Countess' Frightful Screech for the next 24 hours. While {@condition frightened} by this effect, a creature must take the Dash action and move away from the Crimson Countess by the safest available route on each of its turns, unless there is nowhere to move. If the creature ends its turn in a location where it doesn't have line of sight to the Crimson Countess, the creature can repeat the saving throw. On a successful save, the effect ends for that creature.

**Javelin.** {@atk mw,rw} {@hit 8} to hit, reach 5 ft. or ranged 20/60 feet, one target. {@h}9 ({@damage 1d6 + 5}) piercing damage, plus 14 ({@damage 4d6}) lightning damage.

**Thunder Blast {@recharge 5}.** The Crimson Countess unleashes a thunderous cry in a 15-foot cube. Each creature in the cube must succeed on a {@dc 15} Constitution saving throw, taking 14 ({@damage 4d6}) thunder damage on a failed save, or half as much damage on a successful one. Creatures who fail this saving throw are pushed 10 feet and knocked {@condition prone}.

^Tags: #monster #type_monstrosity