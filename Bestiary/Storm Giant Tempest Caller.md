# Storm Giant Tempest Caller

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Storm Giant Tempest Caller | Unknown | 20 | 310 (27d12 + 135) | 17 | walk: 50 ft., fly: {'number': 50, 'condition': '(hover)'} ft., swim: 50 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Lightning Blade | 3d8 + 9 + 3d10 | - | - |
| Lightning Lance | 5d12 + 7 | - | - |
| Tempest Call (Requires Storm Rune) | 8d8 + 7 | 21 | - |


**Multiattack.** The giant makes three Lightning Blade or Lightning Lance attacks.

**Lightning Blade.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}22 ({@damage 3d8 + 9}) slashing damage plus 16 ({@damage 3d10}) lightning damage.

**Lightning Lance.** {@atk rs} {@hit 13} to hit, range 500 ft., one target. {@h}39 ({@damage 5d12 + 7}) lightning damage.

**Tempest Call (Requires Storm Rune).** The giant creates an elemental vortex that fills a 60-foot-radius sphere centered on itself. Each creature in that area other than the giant must make a {@dc 21} Dexterity saving throw. On a failed save, a creature takes 43 ({@damage 8d8 + 7}) damage of a type of the giant's choosing: cold, lightning, or thunder. On a successful save, a creature takes half as much damage.

^Tags: #monster #type_unknown