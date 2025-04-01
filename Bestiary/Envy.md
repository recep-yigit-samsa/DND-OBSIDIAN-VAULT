# Envy

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Envy | Monstrosity | 5 | 114 (12d10 + 48) | 19 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 2d12 + 5 | - | - |
| Claws | 2d10 + 5 | - | - |
| Petrifying Breath {@recharge 5} | - | 13 | - |


**Bite.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}18 ({@damage 2d12 + 5}) piercing damage.

**Claws.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d10 + 5}) bludgeoning damage.

**Petrifying Breath {@recharge 5}.** Envy exhales petrifying gas in a 30-foot cone. Each creature in that area must succeed on a {@dc 13} Constitution saving throw. On a failed save, a target begins to turn to stone and is {@condition restrained}. The {@condition restrained} target must repeat the saving throw at the end of its next turn. On a success, the effect ends on the target. On a failure, the target is {@condition petrified} until freed by the {@spell greater restoration} spell or other magic.

^Tags: #monster #type_monstrosity