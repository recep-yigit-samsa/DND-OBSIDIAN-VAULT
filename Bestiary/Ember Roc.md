# Ember Roc

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ember Roc | Monstrosity | 14 | 232 (16d20 + 64) | 14 | walk: 20 ft., fly: 120 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Beak | 4d8 + 8 + 2d6 | - | - |
| Talons | 4d6 + 8 + 2d6 | - | - |
| Inferno {@recharge 5} | 6d6 | 18 | - |


**Multiattack.** The roc makes two attacks: one with its beak and one with its talons.

**Beak.** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}26 ({@damage 4d8 + 8}) piercing damage and 7 ({@damage 2d6}) fire damage.

**Talons.** {@atk mw} {@hit 13} to hit, reach 5 ft., one target. {@h}22 ({@damage 4d6 + 8}) slashing damage and 7 ({@damage 2d6}) fire damage.

**Inferno {@recharge 5}.** The roc beats its wings, creating a swirling conflagration. Each creature within 30 feet of the roc must succeed on a {@dc 18} Dexterity {@quickref saving throws|PHB|2|1|saving throw} or take 21 ({@damage 6d6}) fire damage.

^Tags: #monster #type_monstrosity