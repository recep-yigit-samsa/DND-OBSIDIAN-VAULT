# Tophet

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tophet | Construct | 8 | 161 (14d12 + 70) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d10 + 5 + 2d6 | 16 | - |
| Burning Belly | 4d6 + 2d6 | 16 | - |
| Gout of Flame {@recharge 5} | 10d6 | 16 | - |


**Multiattack.** The tophet makes two Slam attacks. It can replace one Slam attack with a use of Burning Belly.

**Slam.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}16 ({@damage 2d10 + 5}) bludgeoning damage plus 7 ({@damage 2d6}) fire damage, and the target is {@condition grappled} (escape {@dc 16}) if it is a Large or smaller creature.

**Burning Belly.** The tophet makes one Slam attack against a target it is grappling as it shoves the creature into its open, flame-filled belly. If the attack hits, the target is forced into the tophet's burning belly, and the grapple ends. While inside the belly, the target is {@condition restrained}, has {@quickref Cover||3||three-quarters cover} against attacks and other effects outside the belly, and it takes 14 ({@damage 4d6}) fire damage at the start of each of its turns. A creature, including the target, can take its action to pull the target free from the belly by succeeding on a {@dc 16} Strength check. The creature making the attempt takes 7 ({@damage 2d6}) fire damage.

**Gout of Flame {@recharge 5}.** Flames erupt on a point the tophet can see within 100 feet of it. Each creature within 10 feet of that point must make a {@dc 16} Dexterity saving throw, taking 35 ({@damage 10d6}) fire damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct