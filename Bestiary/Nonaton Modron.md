# Nonaton Modron

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nonaton Modron | Construct | 10 | 161 (19d10 + 57) | 16 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Arm | 2d8 + 4 | 14 | - |
| Pillar of Truth | 6d6 | 15 | - |


**Multiattack.** The nonaton makes three Arm attacks and uses Pillar of Truth or Spellcasting.

**Arm.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage, and if the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 14}). Until this grapple ends, the nonaton can't use this arm against other targets. The nonaton has nine arms, each of which can grapple one target.

**Pillar of Truth.** The nonaton chooses a point on the ground that it can see within 60 feet of itself. A 60-foot-tall, 20-foot-radius cylinder of magical force rises from that point. Each creature in that area must make a {@dc 15} Dexterity saving throw. On a failed save, a creature takes 21 ({@damage 6d6}) force damage, and the creature reverts to its original form (if it's in a different form) and can't assume a different form until the end of its next turn. On a successful save, a creature takes half as much damage only.

^Tags: #monster #type_construct