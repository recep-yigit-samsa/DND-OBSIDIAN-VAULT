# Vapor Lynx

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vapor Lynx | Monstrosity | 5 | 127 (15d10 + 45) | 14 | walk: 50 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 4 | - | - |
| Claw | 2d6 + 4 | - | - |
| Poison Breath {@recharge 5} | 8d6 | 14 | - |


**Multiattack.** The vapor lynx makes one Bite attack and two Claw attacks.

**Bite.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage.

**Claw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage.

**Poison Breath {@recharge 5}.** The vapor lynx exhales poisonous fog in a 20-foot radius centered on itself. The fog spreads around corners, and its area is heavily obscured. Each creature in the area must make a {@dc 14} Constitution saving throw. On a failure, a creature takes 28 ({@damage 8d6}) poison damage and is {@condition poisoned} until the end of its next turn. On a success, a creature takes half the damage and isn't {@condition poisoned}. The fog lasts for 1 minute. A creature that starts its turn in the fog or enters the fog for the first time on a turn must succeed on a {@dc 14} Constitution saving throw or be {@condition poisoned} until the end of its next turn.

^Tags: #monster #type_monstrosity