# Gray Thirster

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gray Thirster | Undead | 2 | 52 (8d8 + 16) | 13 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d4 + 3 | - | - |
| Withering Turban | 1d8 + 3 | 12 | - |
| Drought (1/Day) | 2d8 | 12 | - |


**Multiattack.** The gray thirster makes two Claw attacks, or it makes one Claw attack and one Withering Turban attack.

**Claw.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}8 ({@damage 2d4 + 3}) slashing damage.

**Withering Turban.** {@atk mw} {@hit 5} to hit, reach 10 ft., one creature. {@h}7 ({@damage 1d8 + 3}) necrotic damage. The target must succeed on a {@dc 12} Constitution saving throw or its hp maximum is reduced by an amount equal to the damage taken. The target has disadvantage on this saving throw if it failed the saving throw against the thirster's Thirst Aura. This reduction lasts until the target finishes a long rest with no levels of {@condition exhaustion}. The target dies if this effect reduces its hp maximum to 0.

**Drought (1/Day).** The gray thirster draws the moisture from containers and creatures around it. Nonmagical water and other liquids within 20 feet of the thirster that aren't being worn or carried turn to dust. Each creature within 20 feet of the thirster that isn't a Construct or Undead must make a {@dc 12} Constitution saving throw. On a failure, a creature takes 9 ({@damage 2d8}) necrotic damage and up to 5 gallons of nonmagical liquid it is wearing or carrying turn to dust. On a success, a creature takes half the damage, and nonmagical liquids it is wearing or carrying don't turn to dust. Plants, Oozes, creatures with the Amphibious or Water Breathing trait, and creatures made mostly of water, such as water elementals or steam mephitis, have disadvantage on the saving throw.

^Tags: #monster #type_undead