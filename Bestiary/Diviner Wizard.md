# Diviner Wizard

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Diviner Wizard | Unknown | 8 | 90 (20d8) | 12, 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Arcane Burst | 3d10 + 4 | - | - |
| Overwhelming Revelation {@recharge 5} | 10d8 | 15 | - |


**Multiattack.** The diviner makes three Arcane Burst attacks.

**Arcane Burst.** {@atk ms,rs} {@hit 7} to hit, reach 5 ft. or range 120 ft., one target. {@h}20 ({@damage 3d10 + 4}) radiant damage.

**Overwhelming Revelation {@recharge 5}.** The diviner magically creates a burst of illumination in a 10-foot-radius sphere centered on a point within 120 feet of it. Each creature in that area must make a {@dc 15} Wisdom saving throw. On a failed save, a creature takes 45 ({@damage 10d8}) psychic damage and is {@condition stunned} until the end of the diviner's next turn. On a successful save, the creature takes half as much damage and isn't {@condition stunned}.

^Tags: #monster #type_unknown