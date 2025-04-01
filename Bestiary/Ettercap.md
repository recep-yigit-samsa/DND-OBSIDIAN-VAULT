# Ettercap

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ettercap | Monstrosity | 2 | 44 (8d8 + 8) | 13 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 2 + 1d4 | - | - |
| Claw | 2d4 + 2 | - | - |
| Web Strand {@recharge 5} | - | 12 | - |


**Multiattack.** The ettercap makes one Bite attack and one Claw attack.

**Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}5 ({@damage 1d6 + 2}) Piercing damage plus 2 ({@damage 1d4}) Poison damage, and the target has the {@condition Poisoned|XPHB} condition until the start of the ettercap's next turn.

**Claw.** {@atkr m} {@hit 4}, reach 5 ft. {@h}7 ({@damage 2d4 + 2}) Slashing damage.

**Web Strand {@recharge 5}.** {@actSave dex} {@dc 12}, one Large or smaller creature the ettercap can see within 30 feet. {@actSaveFail} The target has the {@condition Restrained|XPHB} condition until the web is destroyed (AC 10; HP 5; {@variantrule Vulnerability|XPHB} to Fire damage; {@variantrule Immunity|XPHB} to Bludgeoning, Poison, and Psychic damage).

^Tags: #monster #type_monstrosity