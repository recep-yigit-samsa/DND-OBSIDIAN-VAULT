# Swarm of Wolf Spirits

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Swarm of Wolf Spirits | Unknown | 6 | 104 (16d10 + 16) | 16 | walk: 50 ft., fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Spectral Bites | 4d6 + 2d8 + 2d6 + 1d8 | - | - |
| Chilling Howl {@recharge 5} | 10d6 | 15 | - |


**Multiattack.** The swarm of wolf spirits makes two Spectral Bites attacks.

**Spectral Bites.** {@atk mw} {@hit 7} to hit, reach 0 ft., one creature in the swarm's space. {@h}14 ({@damage 4d6}) cold damage plus 9 ({@damage 2d8}) necrotic damage, or 7 ({@damage 2d6}) cold damage plus 4 ({@damage 1d8}) necrotic damage if the swarm has half of its hp or fewer.

**Chilling Howl {@recharge 5}.** The swarm of wolf spirits howls, causing cold fear to course through those that hear it. Each creature within 15 feet that can hear the howl must make a {@dc 15} Constitution saving throw. On a failure, a creature takes 35 ({@damage 10d6}) cold damage and is {@condition frightened} for 1 minute. On a success, a creature takes half the damage and isn't {@condition frightened}. A creature that fails the saving throw by 5 or more also suffers one level of {@condition exhaustion}. A {@condition frightened} creature can make a {@dc 15} Wisdom saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_unknown