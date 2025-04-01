# Vampire

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vampire | Undead | {'cr': '13', 'xpLair': 11500} | 195 (23d8 + 92) | 16 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack (Vampire Form Only) | - | - | - |
| Grave Strike (Vampire Form Only) | 1d8 + 4 + 2d6 | 14 | - |
| Bite (Bat or Vampire Form Only) | 1d4 + 4 + 3d8 | 17 | - |


**Multiattack (Vampire Form Only).** The vampire makes two Grave Strike attacks and uses Bite.

**Grave Strike (Vampire Form Only).** {@atkr m} {@hit 9}, reach 5 ft. {@h}8 ({@damage 1d8 + 4}) Bludgeoning damage plus 7 ({@damage 2d6}) Necrotic damage. If the target is a Large or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 14}) from one of two hands.

**Bite (Bat or Vampire Form Only).** {@actSave con} {@dc 17}, one creature within 5 feet that is willing or that has the {@condition Grappled|XPHB}, {@condition Incapacitated|XPHB}, or {@condition Restrained|XPHB} condition. {@actSaveFail} 6 ({@damage 1d4 + 4}) Piercing damage plus 13 ({@damage 3d8}) Necrotic damage. The target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains {@variantrule Hit Points|XPHB} equal to that amount. A Humanoid reduced to 0 {@variantrule Hit Points|XPHB} by this damage and then buried rises the following sunset as a {@creature Vampire Spawn|XMM} under the vampire's control.

^Tags: #monster #type_undead