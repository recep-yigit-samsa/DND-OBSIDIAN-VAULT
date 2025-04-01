# Swarm of Fire Dancers

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Swarm of Fire Dancers | Unknown | 7 | 90 (12d8 + 36) | 15 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Singe | 4d10 + 2d10 | - | - |
| Frightening Visage {@recharge 5} | - | 16 | - |


**Multiattack.** The swarm of fire dancers can use its Frightening Visage, if available. It then makes two Singe attacks.

**Singe.** {@atk mw} {@hit 8} to hit, reach 0 ft., one target in the swarm's space. {@h}22 ({@damage 4d10}) fire damage, or 11 ({@damage 2d10}) fire damage if the swarm has half its hp or fewer.

**Frightening Visage {@recharge 5}.** The swarm rearranges itself into the shape of a giant, blue, flaming Humanoid skull. Each Humanoid within 30 feet of the swarm that can see it must succeed on a {@dc 16} Wisdom saving throw or be {@condition frightened} for 1 minute. A {@condition frightened} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown