# Giant Goose

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Goose | Fey | 3 | 60 (8d10 + 16) | 13 | walk: 30 ft., fly: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Beak | 2d6 + 2 | - | - |
| Wing | 1d10 + 2 | 12 | - |
| Thunderous Honk {@recharge 5} | 3d10 | 12 | - |


**Multiattack.** The goose makes one Beak attack and two Wing attacks.

**Beak.** {@atk mw} {@hit 4} to hit, reach 10 ft., one target. {@h}9 ({@damage 2d6 + 2}) bludgeoning damage.

**Wing.** {@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d10 + 2}) bludgeoning damage, and the target must succeed on a {@dc 12} Strength saving throw or have the {@condition prone} condition.

**Thunderous Honk {@recharge 5}.** The goose honks with ear-splitting volume. Each other creature within 30 feet of the goose must make a {@dc 12} Constitution saving throw. On a failed save, a creature takes 16 ({@damage 3d10}) thunder damage and has the {@condition deafened} condition until the start of the goose's next turn. On a successful save, a creature takes half as much damage only. The honk can be heard within 300 feet.

^Tags: #monster #type_fey