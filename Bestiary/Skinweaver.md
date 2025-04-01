# Skinweaver

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Skinweaver | Aberration | 3 | 68 (8d10 + 24) | 17 | walk: 30 ft., climb: 15 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tanning Knife | 2d8 + 2 | - | - |
| Web Whip | 2d4 + 2 | - | - |
| Web Net {@recharge 5} | - | 13 | - |


**Multiattack.** The skinweaver makes two tanning knife attacks or one tanning knife and one web whip attack.

**Tanning Knife.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d8 + 2}) slashing damage.

**Web Whip.** {@atk rw} Attack: {@hit 4} to hit, reach 25 ft., one target. {@h}7 ({@damage 2d4 + 2}) piercing damage, and the target is pulled up to 20 feet toward the skinweaver.

**Web Net {@recharge 5}.** {@atk rw} {@hit 4} to hit, range 30/60 ft., one creature. {@h}The target is {@condition restrained} by leathery webbing. As an action, the {@condition restrained} target can attempt a {@dc 13} Strength check, bursting the webbing on a success. The webbing can also be attacked and destroyed (AC 10; hp 10; vulnerability to slashing damage; immunity to bludgeoning, poison, and psychic damage).

^Tags: #monster #type_aberration