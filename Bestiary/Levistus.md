# Levistus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Levistus | Unknown | 26 | 336 (32d8 + 192) | 23 | walk: 0 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Touch of Stygia | 3d8 + 7 | 23 | - |
| Ice Bolt | 3d10 + 7 | - | - |
| Blizzard {@recharge 4} | 3d8 + 3d8 | 23 | - |


**Multiattack.** Levistus makes three Touch of Stygia or Ice Bolt attacks. He can replace one of the attacks with Blizzard (if available).

**Touch of Stygia.** {@atk ms} {@hit 15} to hit, reach 5 ft., one target. {@h}20 ({@damage 3d8 + 7}) psychic damage, and the target must succeed on a {@dc 23} Intelligence saving throw or have the {@condition stunned} condition for 1 minute. The target may repeat the saving throw at the end of its turns, ending the effect on a success. A creature that succeeds on the saving throw is immune to this effect for 1 hour.

**Ice Bolt.** {@atk rs} {@hit 15} to hit, range 120 ft., one target. {@h}23 ({@damage 3d10 + 7}) cold damage.

**Blizzard {@recharge 4}.** Levistus chooses a point he can see within 300 feet of him. Each creature in a 20-foot-radius, 40-foot-high cylinder centered on that point must make a {@dc 23} Dexterity saving throw. Targets take 13 ({@damage 3d8}) force damage plus 13 ({@damage 3d8}) cold damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_unknown