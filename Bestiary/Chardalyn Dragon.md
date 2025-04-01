# Chardalyn Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Chardalyn Dragon | Construct | 11 | 147 (14d12 + 56) | 17 | walk: 30 ft., fly: 90 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d6 + 7 | - | - |
| Tail | 2d10 + 7 | - | - |
| Wings | 2d4 + 7 | - | - |
| Malevolent Presence | - | 16 | - |
| Radiant Breath {@recharge 5} | 7d8 | 16 | - |


**Multiattack.** The dragon uses its Malevolent Presence. It then makes three attacks: two with its claws and one with its tail. If the dragon isn't flying, it can also make one attack with its wings.

**Claw.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d6 + 7}) slashing damage.

**Tail.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}18 ({@damage 2d10 + 7}) bludgeoning damage.

**Wings.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d4 + 7}) bludgeoning damage.

**Malevolent Presence.** Any creature with an Intelligence of 4 or more that is within 30 feet of the dragon must succeed on a {@dc 16} Wisdom saving throw or be {@condition charmed} by it for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Malevolent Presence for the next 24 hours. A creature {@condition charmed} in this way fixates on another creature or object that the dragon mentally chooses and must, on each of its turns, move as close as it can to that target and use its action to make a melee attack against it. If the dragon doesn't choose a target, the {@condition charmed} creature can act normally on its turn.

**Radiant Breath {@recharge 5}.** The dragon exhales a ray of radiant energy in a 120-foot line that is 5 feet wide. Each creature in that line must make a {@dc 16} Dexterity saving throw, taking 31 ({@damage 7d8}) radiant damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct