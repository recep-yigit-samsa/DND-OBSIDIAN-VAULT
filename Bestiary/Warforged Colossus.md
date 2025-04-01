# Warforged Colossus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Warforged Colossus | Construct | 25 | 410 (20d20 + 200) | 23 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 3d12 + 10 | - | - |
| Eldritch Turret | 4d8 | - | - |
| Stomp | 6d10 | 26 | - |
| Incinerating Beam {@recharge 5} | 11d10 | 26 | - |


**Multiattack.** The colossus makes three attacks—one with its slam and two with its eldritch turrets—and then uses Stomp.

**Slam.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}29 ({@damage 3d12 + 10}) bludgeoning damage, and the colossus can push the target up to 20 feet away from it.

**Eldritch Turret.** {@atk rs} {@hit 18} to hit, range 300 ft., one target. {@h}18 ({@damage 4d8}) force damage, and if the target is a creature, it is knocked {@condition prone}.

**Stomp.** The colossus stomps one of its feet at a point on the ground within 20 feet of it. Any creature in a 20-foot-radius, 20-foot-high cylinder centered on this point must succeed on a {@dc 26} Dexterity saving throw or take 33 ({@damage 6d10}) bludgeoning damage and fall {@condition prone}. Until the colossus uses its Stomp again or moves, the creature is {@condition restrained}. While {@condition restrained} in this way, the creature (or another creature within 5 feet of it) can use its action to make a {@dc 26} Strength check. On a success, the creature relocates to an unoccupied space of its choice within 5 feet of the colossus and is no longer {@condition restrained}. Structures, as well as nonmagical objects that are neither being worn nor carried, take the same amount of damage if they are in the cylinder (no save).

**Incinerating Beam {@recharge 5}.** The colossus fires a beam of light in a 150-foot line that is 10 feet wide. Each creature in the line must make a {@dc 26} Dexterity saving throw, taking 60 ({@damage 11d10}) radiant damage on a failed save, or half as much damage on a successful one. A creature reduced to 0 hit points by this beam is disintegrated, leaving behind anything it was wearing or carrying.

^Tags: #monster #type_construct