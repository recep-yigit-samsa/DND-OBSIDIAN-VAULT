# Vampire Spawn

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vampire Spawn | Undead | 5 | 90 (12d8 + 36) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d4 + 3 | 13 | - |
| Bite | 1d4 + 3 + 3d6 | 14 | - |


**Multiattack.** The vampire makes two Claw attacks and uses Bite.

**Claw.** {@atkr m} {@hit 6}, reach 5 ft. {@h}8 ({@damage 2d4 + 3}) Slashing damage. If the target is a Medium or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 13}) from one of two claws.

**Bite.** {@actSave con} {@dc 14}, one creature within 5 feet that is willing or that has the {@condition Grappled|XPHB}, {@condition Incapacitated|XPHB}, or {@condition Restrained|XPHB} condition. {@actSaveFail} 5 ({@damage 1d4 + 3}) Piercing damage plus 10 ({@damage 3d6}) Necrotic damage. The target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains {@variantrule Hit Points|XPHB} equal to that amount.

^Tags: #monster #type_undead