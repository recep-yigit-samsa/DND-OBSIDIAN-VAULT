# Flesh Colossus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Flesh Colossus | Construct | 20 | 280 (16d20 + 112) | 14 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Fist | 3d6 + 7 | 17 | - |
| Elemental Breath {@recharge 5} | 9d8 + 9d8 | 21 | - |


**Multiattack.** The colossus makes two Fist attacks.

**Fist.** {@atk mw} {@hit 13} to hit (with advantage if the colossus is berserk), reach 20 ft., one target. {@h}17 ({@damage 3d6 + 7}) bludgeoning damage. If the target is a Large or smaller creature, it is pulled up to 15 feet toward the colossus, it has the {@condition grappled} condition (escape {@dc 17}), and it has the {@condition restrained} condition until this grapple ends. The colossus can have up to two creatures {@condition grappled} this way at a time.

**Elemental Breath {@recharge 5}.** The colossus exhales a cloud swirling with elemental energy in a 90-foot cone. Each creature in that area must make a {@dc 21} Dexterity saving throw. On a failed save, a creature takes 40 ({@damage 9d8}) damage of a type of the colossus's choosing: acid, cold, fire, or lightning. On a successful save, a creature takes half as much damage. At the same time as the colossus releases this exhalation, creatures inside the colossus's chest cavity take 40 ({@damage 9d8}) force damage from churning elemental energy.

^Tags: #monster #type_construct