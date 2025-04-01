# Euryale

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Euryale | Unknown | 18 | 297 (35d8 + 140) | 17 | walk: 30 ft., alternate: {'walk': [{'number': 50, 'condition': 'in serpent form'}], 'climb': [{'number': 50, 'condition': 'in serpent form'}]} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Constrict (Serpent Form Only) | 2d10 + 5 + 2d10 | 19 | - |
| Snake Bite | 2d6 + 5 | 18 | - |
| Verdant Bolt (Medusa Form Only) | 4d8 | - | - |


**Multiattack.** Euryale makes three attacks. If she is in serpent form, only one of these attacks can be Constrict.

**Constrict (Serpent Form Only).** {@atk mw} {@hit 11} to hit, reach 15 ft., one Large or smaller creature. {@h}16 ({@damage 2d10 + 5}) bludgeoning damage, and the target has the {@condition grappled} condition (escape {@dc 19}). Until this grapple ends, the target takes 11 ({@damage 2d10}) bludgeoning damage at the start of each of its turns, and Euryale can't constrict another target.

**Snake Bite.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage, and the target must succeed on a {@dc 18} Constitution saving throw or have the {@condition poisoned} condition until the start of Euryale's next turn.

**Verdant Bolt (Medusa Form Only).** {@atk rs} {@hit 11} to hit, range 120 ft., one target. {@h}18 ({@damage 4d8}) acid damage.

^Tags: #monster #type_unknown