# Cradle of the Frost Scion

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cradle of the Frost Scion | Elemental | 24 | 499 (27d20 + 216) | 20 | walk: 40 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d10 + 8 + 2d10 | - | - |
| Hurl Icicle | 4d8 + 8 + 2d8 | 23 | - |
| Freezing Breath {@recharge 5} | 8d12 | 23 | No Damage ❌ |


**Multiattack.** The cradle makes two Slam or Hurl Icicle attacks.

**Slam.** {@atk mw} {@hit 15} to hit, reach 20 ft., one target. {@h}30 ({@damage 4d10 + 8}) bludgeoning damage plus 11 ({@damage 2d10}) cold damage.

**Hurl Icicle.** {@atk rw} {@hit 15} to hit, range 120 ft., one target. {@h}26 ({@damage 4d8 + 8}) piercing damage plus 9 ({@damage 2d8}) cold damage, and the target must succeed on a {@dc 23} Strength saving throw or have the {@condition prone} condition.

**Freezing Breath {@recharge 5}.** The cradle exhales a blast of frost in a 90-foot cone. Each creature in that area must make a {@dc 23} Constitution saving throw. On a failed save, a creature takes 52 ({@damage 8d12}) cold damage, and its speed is reduced to 0 until the end of its next turn. On a successful save, a creature takes half as much damage only. If this damage would reduce the target to 0 hit points, the target drops to 1 hit point instead and has the {@condition petrified} condition, turning into a frozen statue. If the statue takes bludgeoning damage, it shatters, killing the frozen creature. If the statue would take fire damage, it instead takes no damage and thaws, ending the petrification.

^Tags: #monster #type_elemental