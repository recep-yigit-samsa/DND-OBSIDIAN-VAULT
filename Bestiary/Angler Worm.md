# Angler Worm

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Angler Worm | Monstrosity | 4 | 104 (11d12 + 33) | 14 | walk: 20 ft., climb: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 2 + 1d6 | - | - |
| Coils | 3d6 + 2 + 3d6 | 13 | - |
| Ethereal Lure {@recharge 4} | - | 13 | - |


**Multiattack.** The angler worm makes two Bite attacks or one Bite attack and one Coils attack.

**Bite.** {@atk mw} {@hit 4} to hit, reach 5 ft., one creature. {@h}9 ({@damage 2d6 + 2}) piercing damage plus 3 ({@damage 1d6}) acid damage.

**Coils.** {@atk mw} {@hit 4} to hit, reach 10 ft., one creature. {@h}12 ({@damage 3d6 + 2}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 13}). Until this grapple ends, the target is {@condition restrained} by the angler worm, it can't breathe, it takes 10 ({@damage 3d6}) bludgeoning damage at the start of each of the angler worm's turns, and the angler worm can't use its Coils on another target.

**Ethereal Lure {@recharge 4}.** The angler worm creates an orb of faint, blue light on a point it can see within 20 feet of it. The light glows until the start of the worm's next turn. When a creature that isn't an angler worm starts its turn within 60 feet of the orb and can see the light, it must succeed on a {@dc 13} Wisdom saving throw or be {@condition charmed} until the start of its next turn. While {@condition charmed}, the creature must take the Dash action and move toward the light by the most direct route, trying to get within 5 feet of the light. It doesn't avoid opportunity attacks, but before moving into damaging terrain, such as lava or a pit, the creature can repeat the saving throw, ending the effect on itself on a success. If the {@condition charmed} creature enters the worm's snares, it has disadvantage on the saving throw to avoid being {@condition restrained}.

^Tags: #monster #type_monstrosity