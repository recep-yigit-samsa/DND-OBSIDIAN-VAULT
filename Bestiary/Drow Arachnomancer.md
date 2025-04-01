# Drow Arachnomancer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Drow Arachnomancer | Unknown | 13 | 162 (25d8 + 50) | 15 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | 4d12 | - | - |
| Poisonous Touch (Humanoid Form Only) | 8d6 | - | - |
| Bite (Giant Spider Form Only) | 2d8 + 3 + 4d12 | 15 | - |
| Web (Giant Spider Form Only Recharge 5–6) | - | 15 | - |


**Multiattack.** The drow makes two poisonous touch attacks or two bite attacks. The first of these attacks that hits each round deals an extra 26 ({@damage 4d12}) poison damage to the target.

**Poisonous Touch (Humanoid Form Only).** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}28 ({@damage 8d6}) poison damage.

**Bite (Giant Spider Form Only).** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d8 + 3}) piercing damage, and the target must make a {@dc 15} Constitution saving throw, taking 26 ({@damage 4d12}) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but {@condition poisoned} for 1 hour, even after regaining hit points, and is {@condition paralyzed} while {@condition poisoned} in this way.

**Web (Giant Spider Form Only Recharge 5–6).** {@atk rw} {@hit 8} to hit, range 30/60 ft., one target. {@h}The target is {@condition restrained} by webbing. As an action, the {@condition restrained} target can make a {@dc 15} Strength check, bursting the webbing on a success. The webbing can also be attacked and destroyed (AC 10; hp 5; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage).

^Tags: #monster #type_unknown