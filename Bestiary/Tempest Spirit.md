# Tempest Spirit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tempest Spirit | Undead | 15 | 195 (17d12 + 85) | 12 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Lightning Fist | 4d8 + 7 | - | - |
| Hailstone | 3d6 + 7 + 2d6 | - | - |
| Death Bolt {@recharge 5} | 6d8 + 3d10 | 18 | - |


**Multiattack.** The spirit makes two Lightning Fist or Hailstone attacks in any combination.

**Lightning Fist.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}25 ({@damage 4d8 + 7}) lightning damage.

**Hailstone.** {@atk rw} {@hit 12} to hit, range 90/180 ft., one target. {@h}17 ({@damage 3d6 + 7}) bludgeoning damage plus 7 ({@damage 2d6}) cold damage.

**Death Bolt {@recharge 5}.** The spirit hurls a magical lightning bolt in a 120-foot line that is 10 feet wide. Each creature in that area must make a {@dc 18} Dexterity saving throw, taking 27 ({@damage 6d8}) lightning damage plus 16 ({@damage 3d10}) necrotic damage on a failed save, or half as much damage on a successful one. On a success or failure, an affected creature's hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the creature finishes a long rest. The creature dies if its hit point maximum is reduced to 0.

^Tags: #monster #type_undead