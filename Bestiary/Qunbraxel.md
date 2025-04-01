# Qunbraxel

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Qunbraxel | Unknown | 9 | 112 (15d8 + 45) | 12, 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 2d10 + 4 | 16 | - |
| Eldritch Bolt | 3d10 + 4 | - | - |
| Extract Brain | 10d10 | - | - |
| Mind Blast {@recharge 5} | 5d8 + 4 | 16 | - |


**Multiattack.** Qunbraxel makes two Eldritch Bolt attacks, or one Eldritch Bolt attack and one Tentacle attack.

**Tentacle.** {@atk mw} {@hit 8} to hit, reach 5 ft., one creature. {@h}15 ({@damage 2d10 + 4}) psychic damage. If the target is Medium or smaller, it has the {@condition grappled} condition (escape {@dc 16}) and must succeed on a {@dc 16} Intelligence saving throw or have the {@condition stunned} condition until the grapple ends.

**Eldritch Bolt.** {@atk rs} {@hit 8} to hit, range 120 ft., one target. {@h}20 ({@damage 3d10 + 4}) force damage.

**Extract Brain.** {@atk mw} {@hit 8} to hit, reach 5 ft., one Humanoid with the {@condition stunned} condition who is {@condition grappled} by Qunbraxel. {@h}55 ({@damage 10d10}) piercing damage. If this damage reduces the target to 0 hit points, Qunbraxel kills it by extracting and devouring its brain.

**Mind Blast {@recharge 5}.** Qunbraxel magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a {@dc 16} Intelligence saving throw or take 26 ({@damage 5d8 + 4}) psychic damage and have the {@condition stunned} condition for 1 minute. A {@condition stunned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown