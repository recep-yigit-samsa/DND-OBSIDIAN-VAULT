# Ancient Mithral Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Mithral Dragon | Dragon | 22 | 490 (28d20 + 196) | 20 | walk: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 8 | - | - |
| Claw | 2d6 + 8 | 23 | - |
| Tail | 2d8 + 8 | - | - |
| Frightful Presence | - | 20 | - |
| Shard Breath {@recharge 5} | 21d6 + 2d6 | 22 | - |


**Multiattack.** The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 15} to hit, reach 15 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage. Instead of dealing damage, the dragon can end one magical effect of its choice of 7th level or lower on the target.

**Claw.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d6 + 8}) slashing damage, and if the target isn't a Construct or Undead, it must succeed on a {@dc 23} Constitution saving throw or lose 10 {@dice 3d6} hp at the start of each of its turns as a piece of metallic claw breaks off in the wound. Any creature can take an action to remove the claw with a successful {@dc 16} Wisdom ({@skill Medicine}) check. The claw pops out of the wound if the target receives magical healing.

**Tail.** {@atk mw} {@hit 15} to hit, reach 20 ft., one target. {@h}17 ({@damage 2d8 + 8}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 20} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Shard Breath {@recharge 5}.** The mithral dragon spits metallic shards in a 90-foot cone. Each creature in that area must succeed on a {@dc 22} Dexterity saving throw, taking 73 ({@damage 21d6}) slashing damage on a failed save, or half as much damage on a successful one. The area becomes difficult terrain for 1 minute, then the shards dissolve into wisps of silvery smoke. When a creature moves into or within the area, it takes 7 ({@damage 2d6}) slashing damage for every 5 feet it travels.

^Tags: #monster #type_dragon