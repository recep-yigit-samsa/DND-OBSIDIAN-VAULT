# Assassin Bug

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Assassin Bug | Monstrosity | 3 | 55 (10d8 + 10) | 14 | walk: 10 ft., fly: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d10 + 2 | 11 | - |
| Ovipositor | 1d6 piercing | - | - |


**Multiattack.** The assassin bug makes two bite attacks.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature. {@h}7 ({@damage 1d10 + 2}) piercing damage, and the target must succeed on a {@dc 11} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned} this way, the target is {@condition paralyzed}. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Ovipositor.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}The target is infested with {@dice 1d3} assassin bug eggs, which immediately hatch into assassin bug maggots. At the start of each of the target's turns, the target takes {@damage 1d6} piercing damage per maggot infesting it. Applying fire to the bite wound before the end of the target's next turn deals 1 fire damage to the target and kills these assassin bug maggots. After this time, the maggots are too far under the skin to be burned. If a target infested by assassin bug maggots ends its turn with 0 hit points, it dies as the maggots burrow into its heart and kill it. Any effect that cures disease kills all assassin bug maggots infesting the target.

^Tags: #monster #type_monstrosity