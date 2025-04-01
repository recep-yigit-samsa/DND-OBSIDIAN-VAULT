# Greater Star Spawn Emissary

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Greater Star Spawn Emissary | Aberration | 21 | 290 (20d12 + 160) | 15 | walk: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Lashing Maw | 2d10 + 7 + 3d8 | - | - |
| Psychic Orb | 3d12 + 8 | - | - |
| Unearthly Bile {@recharge 5} | 10d10 | 23 | - |


**Multiattack.** The emissary makes three attacks.

**Lashing Maw.** {@atk mw} {@hit 14} to hit, reach 15 ft., one target. {@h}20 ({@damage 2d10 + 7}) piercing damage plus 13 ({@damage 3d8}) acid damage.

**Psychic Orb.** {@atk rs} {@hit 15} to hit, range 120 ft., one creature. {@h}27 ({@damage 3d12 + 8}) psychic damage.

**Unearthly Bile {@recharge 5}.** The emissary expels bile that splashes all creatures in a 30-foot-radius sphere centered on a point within 120 feet of the emissary. Each creature in that area must make a {@dc 23} Dexterity saving throw, taking 55 ({@damage 10d10}) acid damage on a failed save, or half as much damage on a successful one. For each creature that fails the saving throw, a {@creature gibbering mouther} (see its entry in the Monster Manual) appears in an unoccupied space on a surface that can support it within 30 feet of that creature. The gibbering mouthers act right after the emissary on the same initiative count, gaining a +7 bonus to their attack and damage rolls, and fighting until they are destroyed. They disappear when the emissary dies.

^Tags: #monster #type_aberration