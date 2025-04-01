# Shator Warden

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shator Warden | Fiend | 14 | 119 (14d10 + 42) | 16 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 7 + 3d6 | - | - |
| Claws | 1d8 + 7 + 2d6 | - | - |
| Poisonous Spit {@recharge 5} | 5d8 | 18 | - |


**Multiattack.** The shator makes one Bite attack or one Poisonous Spit attack (if available) and then makes two Claws attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d8 + 7}) piercing damage plus 10 ({@damage 3d6}) acid damage.

**Claws.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}11 ({@damage 1d8 + 7}) slashing damage plus 7 ({@damage 2d6}) acid damage.

**Poisonous Spit {@recharge 5}.** The shator exhales poisonous spit in a 20-foot line that is 5 feet wide. Each creature in that line must make a {@dc 18} Dexterity saving throw, taking 22 ({@damage 5d8}) acid damage on a failed save and having the {@condition paralyzed} condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on a success.

^Tags: #monster #type_fiend