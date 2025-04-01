# Stormborn Ithjar

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Stormborn Ithjar | Monstrosity | 9 | 189 (18d12 + 72) | 17 | walk: 40 ft., fly: 120 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 5 + 2d8 | - | - |
| Tail | 3d8 + 5 + 2d6 | 17 | - |
| Storm Breath {@recharge 5} | 7d8 + 7d8 | 16 | - |


**Multiattack.** The stormborn ithjar attacks once with its bite and once with its tail.

**Bite.** {@atk mw} {@hit 9} to hit, reach 15 ft., one target. {@h}21 ({@damage 3d10 + 5}) slashing damage and 9 ({@damage 2d8}) lightning damage.

**Tail.** {@atk mw} {@hit 9} to hit, reach 15 ft., one target. {@h}18 ({@damage 3d8 + 5}) bludgeoning damage and 7 ({@damage 2d6}) thunder damage. If the target is a Large or smaller creature, it is {@condition grappled} (escape {@dc 17}). Until this grapple ends, the target is {@condition restrained}, and the stormborn ithjar can't use its tail on another target.

**Storm Breath {@recharge 5}.** The stormborn ithjar exhales a 30-foot cone of lightning and thunder. Each creature in that area must make a {@dc 16} Dexterity saving throw. On a failure, a creature takes 31 ({@damage 7d8}) lightning damage and 31 ({@damage 7d8}) thunder damage and falls {@condition prone}. If the save succeeds, the creature takes half the lightning and thunder damage and doesn't fall {@condition prone}. The discharge of this breath weapon is audible for 1 mile outside and 300 feet inside.

^Tags: #monster #type_monstrosity