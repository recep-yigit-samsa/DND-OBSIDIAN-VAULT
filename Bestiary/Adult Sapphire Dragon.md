# Adult Sapphire Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Sapphire Dragon | Dragon | 15 | 207 (18d12 + 60) | 19 | walk: 40 ft., climb: 40 ft., fly: 80 ft., burrow: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 6 + 1d6 | - | - |
| Claws | 3d8 + 6 | - | - |
| Tail | 2d8 + 6 | - | - |
| Frightful Presence | - | 17 | - |
| Debilitating Breath {@recharge 5} | 13d6 | 18 | - |


**Multiattack.** The dragon can use its Frightful Presence. It then makes two melee attacks, one with its bite and one with its claws.

**Bite.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage plus 3 ({@damage 1d6}) thunder damage.

**Claws.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}19 ({@damage 3d8 + 6}) slashing damage.

**Tail.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d8 + 6}) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 17} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Debilitating Breath {@recharge 5}.** The dragon exhales a pulse of high-pitched, nearly inaudible sound in a 60-foot-cone. Each creature in that cone must make a {@dc 18} Constitution saving throw. On a failed save, the creature takes 45 ({@damage 13d6}) thunder damage and is {@condition incapacitated} until the end of its next turn. On a successful save, the creature takes half as much damage and isn't {@condition incapacitated}.

^Tags: #monster #type_dragon