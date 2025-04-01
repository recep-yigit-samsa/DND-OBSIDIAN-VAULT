# Evoker Wizard

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Evoker Wizard | Unknown | 9 | 121 (22d8 + 22) | 12, 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Arcane Burst | 4d10 + 3 | - | - |
| Sculpted Explosion {@recharge 4} | 9d8 | 15 | - |


**Multiattack.** The evoker makes three Arcane Burst attacks.

**Arcane Burst.** {@atk ms,rs} {@hit 7} to hit, reach 5 ft. or range 120 ft., one target. {@h}25 ({@damage 4d10 + 3}) force damage.

**Sculpted Explosion {@recharge 4}.** The evoker unleashes a magical explosion of a particular damage type: cold, fire, lightning, or thunder. The magic erupts in a 20-foot-radius sphere centered on a point within 150 feet of the evoker. Each creature in that area must make a {@dc 15} Dexterity saving throw. The evoker can select up to three creatures it can see in the area to ignore the spell, as the evoker sculpts the spell's energy around them. On a failed save, a creature takes 40 ({@damage 9d8}) damage of the chosen type and is knocked {@condition prone}. On a successful save, a creature takes half as much damage and isn't knocked {@condition prone}.

^Tags: #monster #type_unknown