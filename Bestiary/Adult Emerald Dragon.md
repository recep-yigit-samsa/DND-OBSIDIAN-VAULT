# Adult Emerald Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Emerald Dragon | Unknown | {'cr': '14', 'lair': '15'} | 207 (18d12 + 90) | 18 | walk: 40 ft., burrow: 30 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 6 + 2d6 | - | - |
| Claw | 1d8 + 6 | - | - |
| Disorienting Breath {@recharge 5} | 12d6 | 18 | - |


**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage plus 7 ({@damage 2d6}) psychic damage.

**Claw.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}10 ({@damage 1d8 + 6}) slashing damage.

**Disorienting Breath {@recharge 5}.** The dragon exhales a wave of psychic dissonance in a 60-foot cone. Each creature in that area must make a {@dc 18} Intelligence saving throw. On a failed save, the creature takes 42 ({@damage 12d6}) psychic damage, and until the end of its next turn, when the creature makes an attack roll or an ability check, it must roll a {@dice d6} and reduce the total by the number rolled. On a successful save, the creature takes half as much damage with no additional effects.

^Tags: #monster #type_unknown