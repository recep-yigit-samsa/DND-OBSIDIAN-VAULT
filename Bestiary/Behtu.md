# Behtu

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Behtu | Humanoid | 2 | 52 (8d6 + 24) | 14 | walk: 20 ft., climb: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 3 | - | - |
| Spear | 1d6 + 3 + 1d8 + 3 | - | - |
| Fire Breath {@recharge} | 6d6 | 13 | - |
| Ichorous Infusion | 3d6 | 14 | - |


**Multiattack.** The behtu makes one Bite attack and one Spear attack.

**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage.

**Spear.** {@atk mw,rw} {@hit 5} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage, or 7 ({@damage 1d8 + 3}) piercing damage if used with two hands to make a melee attack.

**Fire Breath {@recharge}.** The behtu exhales fire in a 15-foot cone. Each creature in that area must make a {@dc 13} Dexterity saving throw, taking 21 ({@damage 6d6}) fire damage on a failed save, or half as much damage on a successful one.

**Ichorous Infusion.** The behtu ingests an infusion made from Mechuiti's blood. For 1 minute, the behtu has advantage on saving throws and ability checks that use Strength and Constitution, and its walking and climbing speeds are doubled. In addition, it has disadvantage on saving throws and ability checks that use Intelligence and Wisdom for the duration. A non-behtu that ingests the infusion must make a {@dc 14} Constitution saving throw. On a failure, the creature takes 10 ({@damage 3d6}) poison damage and is {@condition poisoned} for 1 minute. On a success, the creature takes half the damage and isn't {@condition poisoned}. The behtu typically has {@dice 1d4 + 1} infusions in its possession.

^Tags: #monster #type_humanoid