# Magma Landshark

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Magma Landshark | Elemental | 14 | 150 (12d12 + 72) | 18 | walk: 50 ft., burrow: 50 ft., swim: {'number': 50, 'condition': '(lava only)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 6d12 + 6 + 4d6 + 12d6 | 18 | - |
| Deadly Leap | 6d6 + 6 + 6d6 | 18 | - |
| Lava Pool {@recharge} | 8d10 | - | - |


**Bite.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}45 ({@damage 6d12 + 6}) piercing damage, and 14 ({@damage 4d6}) fire damage. If the target is a Large or smaller creature, it must succeed on a {@dc 18} Dexterity {@quickref saving throws|PHB|2|1|saving throw} or be swallowed by the landshark. A swallowed creature is {@condition blinded} and {@condition restrained}, it has {@quickref cover||3||total cover} against attacks and other effects outside the landshark, and it takes 42 ({@damage 12d6}) fire damage at the start of each of the landshark's turns. If the landshark takes 30 damage or more on a single turn from a creature inside it, the landshark must succeed on a {@dc 23} Constitution {@quickref saving throws|PHB|2|1|saving throw} at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the landshark. If the landshark dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 15 feet of movement, exiting {@condition prone}.

**Deadly Leap.** If the landshark {@quickref jumping|PHB|4|0|jumps} at least 15 feet as part of its movement, it can then use this action to land on its feet in a space that contains one or more other creatures. Each of those creatures must succeed on a {@dc 18} Strength or Dexterity {@quickref saving throws|PHB|2|1|saving throw} (target's choice) or be knocked {@condition prone} and take 27 ({@damage 6d6 + 6}) bludgeoning damage plus 21 ({@damage 6d6}) fire damage. On a successful save, the creature takes only half the damage, isn't knocked {@condition prone}, and is pushed 5 feet out of the landshark's space into an unoccupied space of the creature's choice. If no unoccupied space is within range, the creature instead falls {@condition prone} in the landshark's space.

**Lava Pool {@recharge}.** If the landshark is on solid ground, it melts the area around it, creating a pool of lava in a 10-foot radius. Any creature that starts its turn in the area or enters it for the first time on a turn takes 44 ({@damage 8d10}) fire damage.

^Tags: #monster #type_elemental