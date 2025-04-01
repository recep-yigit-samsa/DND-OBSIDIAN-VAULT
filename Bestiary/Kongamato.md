# Kongamato

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Kongamato | Beast | 6 | 127 (17d10 + 34) | 16 | walk: 10 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Beak | 2d10 + 4 | - | - |
| Claw | 2d8 + 4 | 15 | - |
| Terrifying Screech {@recharge 5} | 8d6 | 15 | - |


**Multiattack.** The kongamato makes one Beak attack and two Claw attacks.

**Beak.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d10 + 4}) piercing damage.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) slashing damage, and the target is {@condition grappled} (escape {@dc 15}) if it is a Medium or smaller creature. The kongamato has two claws, each of which can grapple only one target.

**Terrifying Screech {@recharge 5}.** The kongamato releases a screech in a 30-foot cone. Each creature in the area must make a {@dc 15} Constitution saving throw. On a failure, a creature takes 28 ({@damage 8d6}) thunder damage and is {@condition frightened} until the end of its next turn. On a success, a creature takes half the damage and isn't {@condition frightened}.

^Tags: #monster #type_beast