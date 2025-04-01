# Ruin Spider

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ruin Spider | Monstrosity | 5 | 105 (14d10 + 28) | 16 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Ruinous Bite | 1d8 + 4 + 2d8 | - | - |
| Web {@recharge 5} | - | 13 | - |


**Multiattack.** The spider makes two Ruinous Bite attacks. It can replace one attack with a use of Web.

**Ruinous Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d8 + 4}) piercing damage and 9 ({@damage 2d8}) acid damage. In addition, if the target is a creature wearing nonmagical armor, the armor takes a permanent and cumulative -1 penalty to the AC it offers. Armor reduced to an Armor Class of 10 is destroyed.

**Web {@recharge 5}.** {@atk rw} {@hit 7} to hit, range 30/60 ft., one creature. {@h}The target has the {@condition restrained} condition. As an action, a {@condition restrained} target can make a {@dc 13} Strength check, bursting the webbing on a successful check. The webbing can also be destroyed (AC 10; 5 hit points; vulnerability to fire damage; immunity to acid, bludgeoning, poison, and psychic damage).

^Tags: #monster #type_monstrosity