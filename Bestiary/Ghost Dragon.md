# Ghost Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ghost Dragon | Undead | 17 | 324 (24d12 + 168) | 10 | walk: 40 ft., fly: {'number': 80, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 6d8 + 5 | - | - |
| Claw | 2d8 + 5 | - | - |
| Terrifying Breath {@recharge} | 9d8 | 21 | - |


**Multiattack.** The ghost dragon makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}32 ({@damage 6d8 + 5}) cold damage, and the target's speed is halved until the start of the dragon's next turn.

**Claw.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d8 + 5}) necrotic damage.

**Terrifying Breath {@recharge}.** The ghost dragon exhales shadowy mist in a 90-foot cone. Each creature in that area must make a {@dc 21} Constitution saving throw. On a failed save, the creature takes 40 ({@damage 9d8}) cold damage and is {@condition frightened} of the ghost dragon for 1 minute. On a successful save, the creature takes half as much damage and isn't {@condition frightened}. While {@condition frightened} of the ghost dragon, a creature is {@condition paralyzed}. The {@condition frightened} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to this ghost dragon's Terrifying Breath for the next 24 hours.

^Tags: #monster #type_undead