# Emerald Eye

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Emerald Eye | Construct | 1 | 54 (12d4 + 24) | 14 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Phrenic Burst | 2d6 + 3 | - | - |
| Bind | - | 13 | - |
| Compel | - | 13 | - |


**Phrenic Burst.** {@atk ms,rs} {@hit 5} to hit, range 60 ft., one creature. {@h}10 ({@damage 2d6 + 3}) psychic damage.

**Bind.** The emerald eye chooses a creature it can see within 30 feet of it that has an Intelligence of 6 or higher. The target must succeed on a {@dc 13} Charisma saving throw or the eye psychically binds itself to the target. If the target succeeds on the saving throw by 5 or more, it knows the eye attempted to bind to it. Otherwise, the target is unaware of the attempt. While bound to the emerald eye, the creature has resistance to psychic damage, but it has disadvantage on saving throws against the eye's Compulsion. The eye can be bound to only one target at a time. If it binds to another, the effect on the previous target ends.

**Compel.** The emerald eye magically compels one creature it can see within 30 feet of it to move. The target must succeed on a {@dc 13} Charisma saving throw or be {@condition charmed} by the eye for 1 minute. At the start of each of the {@condition charmed} target's turns, the emerald eye chooses a direction horizontal to the eye, and the target must use as much of its movement as possible to move in that direction on its turn. The target can take its action before it moves. The target can't be compelled to move into an obviously deadly hazard, such as a fire or pit, but it will provoke opportunity attacks to move in the designated direction. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_construct