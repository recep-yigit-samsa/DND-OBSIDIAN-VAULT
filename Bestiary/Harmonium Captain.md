# Harmonium Captain

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Harmonium Captain | Humanoid | 8 | 110 (17d8 + 34) | 20 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Harmonium Blade | 1d10 + 4 + 3d6 | - | - |
| Dictate {@recharge 5} | - | 14 | - |


**Multiattack.** The captain makes three Harmonium Blade attacks. The captain can also use Dictate if available.

**Harmonium Blade.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d10 + 4}) piercing damage plus 10 ({@damage 3d6}) lightning damage.

**Dictate {@recharge 5}.** The captain verbally commands up to three creatures it can see within 60 feet of itself. This magical command must be to undertake an action or to refrain from taking actions (for example, "Throw down your weapons"). A target must succeed on a {@dc 14} Wisdom saving throw or have the {@condition charmed} condition for 1 minute, during which time it follows the captain's command. The effect ends early if the target takes damage or if it successfully completes the command. A target automatically succeeds on its saving throw if the command is directly harmful to itself, such as commanding it to walk into fire. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a successful save.

^Tags: #monster #type_humanoid