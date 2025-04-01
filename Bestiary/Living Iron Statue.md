# Living Iron Statue

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Living Iron Statue | Construct | 5 | 102 (12d8 + 48) | 16 | walk: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Blade | 2d6 + 3 | - | - |
| Hammer | 2d6 + 3 | - | - |
| Whirl {@recharge 5} | 3d10 + 3 | 13 | - |


**Multiattack.** The statue makes two attacks: one with its blade and one with its hammer.

**Blade.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) slashing damage.

**Hammer.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d6 + 3}) bludgeoning damage, and the target is knocked {@condition prone}.

**Whirl {@recharge 5}.** The statue can use its action to spin at the waist, targeting creatures of its choice within 10 feet of it. Each target must make a {@dc 13} Dexterity saving throw, taking 19 ({@damage 3d10 + 3}) bludgeoning damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct