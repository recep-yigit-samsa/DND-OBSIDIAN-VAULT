# Bebilith

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bebilith | Unknown | 12 | 189 (18d12 + 72) | 17 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 3 + 6d6 + 2d6 | - | - |
| Foreleg | 4d8 + 3 | - | - |
| Poisoned Web {@recharge 5} | 10d8 + 6 + 2d8 + 2d6 | 17 | - |
| Stalker's Darkness (3/Day) | - | - | - |


**Multiattack.** The bebilith uses Poisoned Web (if available) and then makes one Bite attack and two Foreleg attacks.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d12 + 3}) piercing damage plus 21 ({@damage 6d6}) poison damage. Any creature that drops to zero hit points because of this attack ignites, suffering 7 ({@damage 2d6}) fire damage at the start of each of its turns until the creature's hit points are above zero.

**Foreleg.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}21 ({@damage 4d8 + 3}) slashing damage.

**Poisoned Web {@recharge 5}.** {@atk rw} {@hit 10} to hit, range 30/60 ft., one creature. {@h}51 ({@damage 10d8 + 6}) poison damage, and the target has the {@condition restrained} condition until free of the web. While {@condition restrained}, the target takes 9 ({@damage 2d8}) poison damage at the start of each of its turns. The target may use an action to make a {@dc 17} Strength check and if successful they are freed from the webbing. The webbing can also be attacked and destroyed (AC 12; 10 hit points; immunity to bludgeoning, fire, poison, and psychic damage). If an attack or spell doing fire damage is used on the webbing, the webbing ignites (but is otherwise unharmed). Any creature {@condition restrained} by the webbing suffers an additional 7 ({@damage 2d6}) fire damage at the start of each of its turn.

**Stalker's Darkness (3/Day).** The bebilith casts {@spell darkness}.

^Tags: #monster #type_unknown