# Relentless Juggernaut

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Relentless Juggernaut | Fiend | 12 | 161 (14d10 + 84) | 17 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Executioner's Pick | 2d10 + 6 | - | - |
| Fist | 1d10 + 6 | 18 | - |
| Deadly Shaping {@recharge 5} | - | 18 | - |
| Flying Stone | 5d8 | - | - |
| Scything Shrapnel | 4d6 + 3d6 | 15 | - |


**Multiattack.** The juggernaut makes two attacks. It can replace one attack with Deadly Shaping if it is ready.

**Executioner's Pick.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage, and if the target is a creature, its speed is reduced by 10 feet until the start of the juggernaut's next turn.

**Fist.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}11 ({@damage 1d10 + 6}) bludgeoning damage, and if the target is a Large or smaller creature, it must succeed on a {@dc 18} Strength saving throw or be knocked {@condition prone}.

**Deadly Shaping {@recharge 5}.** The juggernaut magically shapes a feature of its surroundings into a deadly implement. A creature the juggernaut can see within 60 feet of it must make a {@dc 18} Dexterity saving throw. If the saving throw fails, the targeted creature is struck by one of the following (juggernaut's choice):

**Flying Stone.** The target takes 22 ({@damage 5d8}) bludgeoning damage and is {@condition incapacitated} until the start of the juggernaut's next turn, and the implement vanishes.

**Scything Shrapnel.** The target takes 14 ({@damage 4d6}) slashing damage, and the implement vanishes. At the start of each of its turns, the target takes 10 ({@damage 3d6}) necrotic damage from the wound left by the shrapnel. The wound ends if the target regains any hit points or if a creature uses an action to stanch the wound, which requires a successful {@dc 15} Wisdom ({@skill Medicine}) check.

^Tags: #monster #type_fiend