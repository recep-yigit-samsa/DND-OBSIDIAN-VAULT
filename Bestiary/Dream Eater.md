# Dream Eater

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dream Eater | Fiend | 5 | 75 (10d8 + 30) | 15 | walk: 30 ft., fly: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 4 | - | - |
| Claw | 2d8 + 4 | 14 | - |
| Lotus Scent | - | 14 | - |
| Waking Dreams {@recharge 5} | 6d6 | 14 | - |


**Multiattack.** The dream eater uses its Lotus Scent. It then makes one Bite attack and one Claw attack.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) slashing damage, and the target is {@condition grappled} (escape {@dc 14}) if it is a Large or smaller creature. Until this grapple ends, the creature is {@condition restrained}. The dream eater has two claws, each of which can grapple only one target.

**Lotus Scent.** The dream eater secretes an oily chemical that most creatures find intoxicating. Each creature that isn't a Construct or Undead within 15 feet of the dream eater must succeed on a {@dc 14} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned}, the creature is {@condition charmed} by the fiend. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dream eater's Lotus Scent for the next 24 hours.

**Waking Dreams {@recharge 5}.** Each creature within 20 feet of the dream eater must make a {@dc 14} Charisma saving throw. On a failure, a creature takes 21 ({@damage 6d6}) psychic damage and is {@condition incapacitated} for 1 minute. When it moves, an {@condition incapacitated} creature moves in a random direction. On a success, a creature takes half the damage and isn't {@condition incapacitated}. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_fiend