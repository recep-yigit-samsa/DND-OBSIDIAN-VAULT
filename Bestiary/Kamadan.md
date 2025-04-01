# Kamadan

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Kamadan | Monstrosity | 4 | 67 (9d10 + 18) | 13 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 3 | - | - |
| Claw | 1d6 + 3 | - | - |
| Snakes | 1d6 + 3 + 6d6 | 12 | - |
| Sleep Breath (Recharges after a Short or Long Rest) | - | 12 | - |


**Multiattack.** The kamadan makes two attacks: one with its bite or claw and one with its snakes.

**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage.

**Claw.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) slashing damage.

**Snakes.** {@atk mw} {@hit 5} to hit, reach 5 ft., one creature. {@h}6 ({@damage 1d6 + 3}) piercing damage, and the target must make a {@dc 12} Constitution saving throw, taking 21 ({@damage 6d6}) poison damage on a failed save, or half as much damage on a successful one.

**Sleep Breath (Recharges after a Short or Long Rest).** The kamadan exhales sleep gas in a 30-foot cone. Each creature in that area must succeed on a {@dc 12} Constitution saving throw or fall {@condition unconscious} for 10 minutes. This effect ends for a creature if it takes damage or someone uses an action to wake it.

^Tags: #monster #type_monstrosity