# Istarian Drone

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Istarian Drone | Construct | 6 | 127 (15d8 + 60) | 17 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d8 + 5 + 1d8 | 15 | - |
| Crystalline Spit {@recharge 5} | 4d6 | 15 | - |


**Multiattack.** The drone makes two Claw attacks.

**Claw.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d8 + 5}) piercing damage plus 4 ({@damage 1d8}) lightning damage. If the target is a Medium or smaller creature, it is {@condition grappled} (escape {@dc 15}). The drone has two claws, each of which can grapple only one target.

**Crystalline Spit {@recharge 5}.** The drone spits crackling gel in a line 5 feet wide and 20 feet long. Each creature in the line must make a {@dc 15} Dexterity saving throw. On a failed save, the creature takes 14 ({@damage 4d6}) lightning damage and is {@condition restrained} by the gel, which hardens into crystal. The creature is {@condition restrained} until the crystal is destroyed. The crystal has AC 15, 15 hit points, immunity to poison and psychic damage, and vulnerability to thunder damage. On a successful save, the creature takes half as much damage and isn't {@condition restrained}.

^Tags: #monster #type_construct