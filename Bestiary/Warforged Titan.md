# Warforged Titan

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Warforged Titan | Construct | 8 | 125 (10d12 + 60) | 20 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Axehand | 3d8 + 6 + 2d10 | - | - |
| Hammerfist | 3d8 + 6 | 17 | - |
| Sweeping Axe {@recharge} | 3d8 + 6 | 17 | - |


**Multiattack.** The warforged titan makes one axehand attack and one hammerfist attack.

**Axehand.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}19 ({@damage 3d8 + 6}) slashing damage, plus 11 ({@damage 2d10}) slashing damage if the target is {@condition prone}.

**Hammerfist.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}19 ({@damage 3d8 + 6}) bludgeoning damage. If the target is a creature, it must succeed on a {@dc 17} Strength saving throw or be knocked {@condition prone}.

**Sweeping Axe {@recharge}.** The warforged titan makes a sweep with its axehand, and each creature within 10 feet of it must make a {@dc 17} Dexterity saving throw. A creature takes 19 ({@damage 3d8 + 6}) slashing damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct