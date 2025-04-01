# Big Linda

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Big Linda | Beast | 9 | 136 (13d12 + 52) | 13 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d12 + 7 | 17 | - |
| Tail | 3d8 + 7 | - | - |
| Acid Spew {@recharge 5} | 11d8 | 15 | - |


**Multiattack.** Big Linda makes two attacks: one with its bite and one with its tail. It can't make both attacks against the same target.

**Bite.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}33 ({@damage 4d12 + 7}) piercing damage. If the target is a Medium or smaller creature, it is {@condition grappled} (escape {@dc 17}). Until this grapple ends, the target is {@condition restrained}, and Big Linda can't bite another target.

**Tail.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}20 ({@damage 3d8 + 7}) bludgeoning damage.

**Acid Spew {@recharge 5}.** Big Linda spews acid in a 30 foot cone. Each creature in that line of fire must succeed on a {@dc 15} Dexterity saving throw, taking 49 ({@damage 11d8}) acid damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_beast