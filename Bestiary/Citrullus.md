# Citrullus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Citrullus | Plant | 3 | 85 (10d10 + 30) | 15 | walk: 15 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 4d6 + 4 + 2d6 | - | - |
| Bile Spray {@recharge 5} | 4d6 | 13 | - |


**Bite.** {@atk mw} {@hit 6} to hit, reach 10 ft., one target. {@h}18 ({@damage 4d6 + 4}) piercing damage plus 7 ({@damage 2d6}) acid damage.

**Bile Spray {@recharge 5}.** The citrullus exhales pink bile in a 30-foot cone. Each creature in that area must make a {@dc 13} Dexterity saving throw. On a failure, the creature takes 14 ({@damage 4d6}) acid damage and is {@condition restrained} by the sticky seed-filled juice for 1 minute. On a success, the creature takes half the damage and isn't {@condition restrained}. A creature, including the {@condition restrained} creature, can take its action to free the {@condition restrained} creature by succeeding on a {@dc 13} Strength check.

^Tags: #monster #type_plant