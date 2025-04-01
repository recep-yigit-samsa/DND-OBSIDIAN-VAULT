# Skein Witch

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Skein Witch | Undead | 12 | 162 (25d8 + 50) | 20 | walk: 30 ft., fly: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 17 | - |
| Inexorable Thread | 5d8 + 5 | - | - |
| Destiny Distortion Wave {@recharge 5} | 10d10 | 17 | - |
| Bind Fates (1/Day) | - | 17 | - |


**Multiattack.** The skein witch makes three Inexorable Thread attacks. If two Inexorable Thread attacks hit one creature, the target must succeed on a {@dc 17} Constitution saving throw or have disadvantage on the next death saving throw it makes before it finishes a short rest. If a creature fails this saving throw multiple times, these effects are cumulative, affecting up to three of the creature's next death saving throws before it finishes a short rest.

**Inexorable Thread.** {@atk ms,rs} {@hit 9} to hit, reach 5 ft. or range 60 ft., one creature. {@h}27 ({@damage 5d8 + 5}) radiant damage.

**Destiny Distortion Wave {@recharge 5}.** The skein witch frays the strands of fate in a 60-foot cone. Each creature in the area must make a {@dc 17} Wisdom saving throw, taking 55 ({@damage 10d10}) force damage on a failed save, or half as much damage on a successful one. If any creature that failed the saving throw is affected by a condition, such as {@condition incapacitated} or {@condition poisoned}, those conditions are randomly redistributed among all the creatures that failed the saving throw.

**Bind Fates (1/Day).** One creature within 60 feet of the skein witch must succeed on a {@dc 17} Wisdom saving throw or the target's fate is bound to one of its ally's (chosen at random). Any damage or condition the target suffers is inflicted on the individual to which they are bound instead, and vice versa. A creature can be bound to only one other creature at a time. This binding lasts until lifted by a heal or {@spell heroes' feast} spell or similar magic.

^Tags: #monster #type_undead