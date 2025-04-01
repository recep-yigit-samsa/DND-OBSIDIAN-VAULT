# Zaratan

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Zaratan | Elemental | 22 | 307 (15d20 + 150) | 21 | walk: 40 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d8 + 10 | - | - |
| Stomp | 3d10 + 10 | - | - |
| Spit Rock | 6d8 + 10 | - | - |
| Spew Debris {@recharge 5} | 6d10 | 25 | - |


**Multiattack.** The zaratan makes two attacks: one with its bite and one with its stomp.

**Bite.** {@atk mw} {@hit 17} to hit, reach 20 ft., one target. {@h}28 ({@damage 4d8 + 10}) piercing damage.

**Stomp.** {@atk mw} {@hit 17} to hit, reach 20 ft., one target. {@h}26 ({@damage 3d10 + 10}) bludgeoning damage.

**Spit Rock.** {@atk rw} {@hit 17} to hit, range 120/240 ft., one target. {@h}31 ({@damage 6d8 + 10}) bludgeoning damage.

**Spew Debris {@recharge 5}.** The zaratan exhales rocky debris in a 90-foot cube. Each creature in that area must make a {@dc 25} Dexterity saving throw. A creature takes 33 ({@damage 6d10}) bludgeoning damage on a failed save, or half as much damage on a successful one. A creature that fails the save by 5 or more is knocked {@condition prone}.

^Tags: #monster #type_elemental