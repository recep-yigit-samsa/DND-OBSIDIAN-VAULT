# Rime Worm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Rime Worm | Elemental | 6 | 114 (12d10 + 48) | 15 | walk: 30 ft., swim: 30 ft., burrow: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rime Tendril | 2d6 + 5 + 2d8 | 15 | - |
| Freeze Prey | - | 15 | - |
| Black Ice Spray {@recharge 5} | 8d8 | 15 | - |


**Multiattack.** The rime worm makes two Rime Tendril attacks. It can replace one attack with a use of Freeze Prey.

**Rime Tendril.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) bludgeoning damage plus 9 ({@damage 2d8}) cold damage. The target is {@condition grappled} (escape {@dc 15}) if it is a Medium or smaller creature and the rime worm doesn't have another creature {@condition grappled}.

**Freeze Prey.** One creature {@condition grappled} by the rime worm must succeed on a {@dc 15} Constitution saving throw or be {@condition petrified} in ice for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A {@condition petrified} creature that takes fire damage has advantage on the saving throw.

**Black Ice Spray {@recharge 5}.** The rime worm sprays slivers of ice in a 30-foot cone. Each creature in the area must make a {@dc 15} Constitution saving throw, taking 36 ({@damage 8d8}) cold damage on a failed save, or half as much damage on a successful one. The area then becomes icy, difficult terrain for 1 minute.

^Tags: #monster #type_elemental