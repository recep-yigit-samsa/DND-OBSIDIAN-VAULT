# Spinosaurus Dinosaur

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Spinosaurus Dinosaur | Beast | 13 | 232 (15d20 + 75) | 15 | walk: 60 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d12 + 7 | 18 | - |
| Claw | 4d6 + 7 | - | - |
| Tail | 2d8 + 7 | - | - |
| Frightful Presence | - | 18 | - |


**Multiattack.** The spinosaurus makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}33 ({@damage 4d12 + 7}) piercing damage. If the target is a Large or smaller creature, it is {@condition grappled} (escape {@dc 18}). Until this grapple ends, the target is {@condition restrained}, and the spinosaurus can't Bite another target.

**Claw.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}21 ({@damage 4d6 + 7}) slashing damage.

**Tail.** {@atk mw} {@hit 12} to hit, reach 20 ft., one target. {@h}16 ({@damage 2d8 + 7}) bludgeoning damage.

**Frightful Presence.** Each creature of the spinosaurus' choice that is within 120 feet of the spinosaurus and aware of it must succeed on a {@dc 18} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the spinosaurus's Frightful Presence for the next 24 hours.

^Tags: #monster #type_beast