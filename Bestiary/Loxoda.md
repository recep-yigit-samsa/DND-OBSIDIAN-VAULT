# Loxoda

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Loxoda | Monstrosity | 6 | 147 (14d12 + 56) | 13 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d8 + 4 | - | - |
| Spear | 3d6 + 4 + 3d8 + 4 | - | - |
| Stomp | 3d10 + 4 | - | - |
| Tooth-Rattling Pound {@recharge 5} | 8d8 + 3d6 | 15 | - |


**Multiattack.** The loxoda makes one Slam attack and one Spear attack.

**Slam.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}22 ({@damage 4d8 + 4}) bludgeoning damage.

**Spear.** {@atk mw,rw} {@hit 7} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}14 ({@damage 3d6 + 4}) piercing damage, or 17 ({@damage 3d8 + 4}) piercing damage if used with two hands to make a melee attack.

**Stomp.** {@atk mw} {@hit 7} to hit, reach 5 ft., one {@condition prone} creature. {@h}20 ({@damage 3d10 + 4}) bludgeoning damage.

**Tooth-Rattling Pound {@recharge 5}.** The loxoda rears up and lands heavily, rattling the land and creatures around it. Each creature in contact with the ground within 20 feet of the loxoda must make a {@dc 15} Dexterity saving throw. On a failure, a creature takes 36 ({@damage 8d8}) bludgeoning damage and takes an extra 10 ({@damage 3d6}) thunder damage at the end of its next turn as the shockwaves from the Tooth-Rattling Pound continue up through its body. On a success, a creature takes half the damage and doesn't take extra thunder damage from shockwaves.

^Tags: #monster #type_monstrosity