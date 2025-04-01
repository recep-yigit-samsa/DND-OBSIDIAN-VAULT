# Maelephant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Maelephant | Fiend | 10 | 161 (17d10 + 68) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Barbed Trunk | 2d8 + 4 + 2d12 | 14 | - |
| Glaive | 2d10 + 4 | - | - |
| Mind Poison {@recharge 5} | 6d12 | 16 | - |


**Multiattack.** The maelephant makes one Barbed Trunk attack and two Glaive attacks.

**Barbed Trunk.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage plus 13 ({@damage 2d12}) poison damage. If the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 14}). Until this grapple ends, the target has the {@condition restrained} condition. While it is grappling a creature, the maelephant can't use its barbed trunk to attack other creatures.

**Glaive.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d10 + 4}) slashing damage.

**Mind Poison {@recharge 5}.** The maelephant expels poisonous gas from its trunk in a 60-foot cone. Each creature in that area must make a {@dc 16} Constitution saving throw. On a failed save, a creature takes 39 ({@damage 6d12}) poison damage and has the {@condition poisoned} condition. While {@condition poisoned} in this way, the creature loses all weapon and skill proficiencies, it can't cast spells, it can't understand language, and it has disadvantage on Intelligence saving throws. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, the target takes half as much damage only and is immune to this maelephant's Mind Poison for 24 hours.

^Tags: #monster #type_fiend