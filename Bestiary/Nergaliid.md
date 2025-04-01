# Nergaliid

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nergaliid | Unknown | 3 | 42 (4d10 + 20) | 12 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d8 + 4 | 15 | - |
| Tongue Lash | 1d12 + 4 | - | - |
| Siphon Life {@recharge 4} | 3d6 | 15 | - |


**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one creature. {@h}13 ({@damage 2d8 + 4}) piercing damage, and the target must succeed on a {@dc 15} Constitution saving throw or become {@condition poisoned} for 1 minute. The {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Tongue Lash.** {@atk mw} {@hit 6} to hit, reach 20 ft., one target. {@h}10 ({@damage 1d12 + 4}) bludgeoning damage.

**Siphon Life {@recharge 4}.** The nergaliid magically draws the life from a humanoid it can see within 40 feet of it. The target must make a {@dc 15} Wisdom saving throw. An {@condition incapacitated} target fails the save automatically. On a failed save, the creature takes 10 ({@damage 3d6}) psychic damage, and the nergaliid gains temporary hit points equal to the damage taken. On a successful save, the target takes half as much damage, and the nergaliid doesn't gain temporary hit points. If this damage kills the target, its body rises at the end of the nergaliid's current turn as a {@creature husk zombie|EGW} (see earlier in this chapter).

^Tags: #monster #type_unknown