# Egg Hunter Adult

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Egg Hunter Adult | Monstrosity | 5 | 52 (8d6 + 24) | 16 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Barbed Proboscis | 1d6 + 5 + 2d8 | - | - |
| Torpor Spores {@recharge 5} | - | 14 | - |


**Multiattack.** The egg hunter makes two Barbed Proboscis attacks, and it can use Torpor Spores if it's available.

**Barbed Proboscis.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d6 + 5}) piercing damage plus 9 ({@damage 2d8}) necrotic damage, and the egg hunter regains hit points equal to the necrotic damage dealt.

**Torpor Spores {@recharge 5}.** The egg hunter releases a billow of sparkling blue spores. Each creature in a 30-foot-radius sphere centered on the egg hunter must succeed on a {@dc 14} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned} in this way, the creature can take either an action or a bonus action on its turn but not both, and it can't take reactions. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to this egg hunter's Torpor Spores for the next 24 hours.

^Tags: #monster #type_monstrosity