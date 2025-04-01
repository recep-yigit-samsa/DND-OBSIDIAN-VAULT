# Jotun

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Jotun | Giant | 22 | 370 (20d20 + 160) | 20 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Greatclub | 4d8 + 10 + 6d8 | - | - |
| Rock | 4d10 + 10 + 6d8 | - | - |
| Frightful Presence | - | 20 | - |
| Icy Sweep {@recharge 5} | 8d8 + 12d8 | 23 | - |


**Multiattack.** The jotun can use its Frightful Presence. It then makes three Greatclub or Rock attacks.

**Greatclub.** {@atk mw} {@hit 17} to hit, reach 15 ft., one target. {@h}28 ({@damage 4d8 + 10}) bludgeoning damage plus 27 ({@damage 6d8}) cold damage.

**Rock.** {@atk rw} {@hit 17} to hit, range 60/240 ft., one target. {@h}32 ({@damage 4d10 + 10}) bludgeoning damage plus 27 ({@damage 6d8}) cold damage.

**Frightful Presence.** Each creature of the jotun's choice within 120 feet of the jotun and aware of it must succeed on a {@dc 20} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the jotun's Frightful Presence for the next 24 hours.

**Icy Sweep {@recharge 5}.** The jotun swings its ice-coated greatclub in a wide arc. Each creature within 20 feet of the jotun must make a {@dc 23} Dexterity saving throw. On a failure, a creature takes 36 ({@damage 8d8}) bludgeoning damage and 54 ({@damage 12d8}) cold damage and is pushed up to 15 feet away from the jotun and knocked {@condition prone}. On a success, a creature takes half the damage and isn't pushed or knocked {@condition prone}.

^Tags: #monster #type_giant