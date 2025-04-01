# Adult Mithral Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Mithral Dragon | Dragon | 18 | 253 (22d12 + 110) | 18 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 6 | - | - |
| Claw | 2d6 + 6 | 19 | - |
| Tail | 2d8 + 6 | - | - |
| Frightful Presence | - | 18 | - |
| Shard Breath {@recharge 5} | 12d6 + 2d6 | 19 | - |


**Multiattack.** The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage. Instead of dealing damage, the dragon can end one magical effect of its choice of 5th level or lower on the target.

**Claw.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage, and if the target isn't a Construct or Undead, it must succeed on a {@dc 19} Constitution saving throw or lose 7 {@dice 2d6} hp at the start of each of its turns as a piece of metallic claw breaks off in the wound. Any creature can take an action to remove the claw with a successful {@dc 14} Wisdom ({@skill Medicine}) check. The claw pops out of the wound if the target receives magical healing.

**Tail.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}15 ({@damage 2d8 + 6}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 18} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Shard Breath {@recharge 5}.** The mithral dragon spits metallic shards in a 60-foot cone. Each creature in that area must make a {@dc 19} Constitution saving throw, taking 42 ({@damage 12d6}) slashing damage on a failed save, or half as much on a successful one. The area becomes difficult terrain for 1 minute, then the shards dissolve into wisps of silvery smoke. When a creature moves into or within the area, it takes 7 ({@damage 2d6}) slashing damage for every 5 feet it travels.

^Tags: #monster #type_dragon