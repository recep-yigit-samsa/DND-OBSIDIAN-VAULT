# Giant Spider

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Spider | Beast | 1 | 26 (4d10 + 4) | 14 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d8 + 3 + 2d6 | - | - |
| Web {@recharge 5} | - | 13 | - |


**Bite.** {@atkr m} {@hit 5}, reach 5 ft. {@h}7 ({@damage 1d8 + 3}) Piercing damage plus 7 ({@damage 2d6}) Poison damage.

**Web {@recharge 5}.** {@actSave dex} {@dc 13}, one creature the spider can see within 60 feet. {@actSaveFail} The target has the {@condition Restrained|XPHB} condition until the web is destroyed (AC 10; HP 5; {@variantrule Vulnerability|XPHB} to Fire damage; {@variantrule Immunity|XPHB} to Poison and Psychic damage).

^Tags: #monster #type_beast