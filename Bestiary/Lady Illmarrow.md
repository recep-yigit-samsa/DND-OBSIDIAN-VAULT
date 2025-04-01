# Lady Illmarrow

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lady Illmarrow | Undead | 22 | 199 (21d8 + 105) | 19 | walk: 30 ft., fly: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Chill Touch (Cantrip) | 4d8 | - | - |
| Paralyzing Claw | 3d6 + 3 + 3d6 | 20 | - |
| Poison Breath {@recharge 5} | 10d6 | 20 | - |


**Chill Touch (Cantrip).** {@atk rs} {@hit 15} to hit, range 120 ft., one creature. {@h}18 ({@damage 4d8}) necrotic damage, and the target can't regain hit points until the start of Illmarrow's next turn. If the target is undead, it also has disadvantage on attack rolls against Illmarrow until the end of her next turn.

**Paralyzing Claw.** {@atk mw} {@hit 10} to hit, reach 5 ft., one creature. {@h}13 ({@damage 3d6 + 3}) slashing damage plus 10 ({@damage 3d6}) cold damage, and the target must succeed on a {@dc 20} Constitution saving throw or be {@condition paralyzed} for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Poison Breath {@recharge 5}.** Illmarrow exhales poisonous gas in a 30-foot cone. Each creature in that area must make a {@dc 20} Constitution saving throw. On a failed save, a creature takes 35 ({@damage 10d6}) poison damage and is {@condition poisoned} for 1 minute. While {@condition poisoned} in this way, the creature can't regain hit points. On a successful save, the creature takes half as much damage and isn't {@condition poisoned}. A humanoid reduced to 0 hit points by this damage dies and rises at the start of Illmarrow's next turn as a zombie. The zombie acts immediately after Illmarrow in the initiative count and is permanently under her command, following her verbal orders.

^Tags: #monster #type_undead