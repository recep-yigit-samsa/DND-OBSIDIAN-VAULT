# Gearkeeper Construct

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gearkeeper Construct | Construct | 10 | 161 (17d10 + 68) | 18 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Arm Blade | 3d8 + 5 | - | - |
| Spear Launcher | 2d6 + 5 | - | - |
| Shrapnel Blast {@recharge} | 6d6 | 15 | - |


**Multiattack.** The gearkeeper makes two Arm Blade attacks, or one Arm Blade attack and one Spear Launcher attack.

**Arm Blade.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}18 ({@damage 3d8 + 5}) slashing damage.

**Spear Launcher.** {@atk rw} {@hit 9} to hit, range 90 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage, and the target is knocked {@condition prone}.

**Shrapnel Blast {@recharge}.** The gearkeeper jettisons a spray of jagged metal in a 30-foot cone. Each creature in the area must make a {@dc 15} Dexterity saving throw, taking 21 ({@damage 6d6}) piercing damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct