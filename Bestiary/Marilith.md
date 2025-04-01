# Marilith

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Marilith | Unknown | 16 | 220 (21d10 + 105) | 16 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pact Blade | 1d10 + 5 + 2d6 | - | - |
| Constrict | 2d10 + 4 | 17 | - |


**Multiattack.** The marilith makes six Pact Blade attacks and uses Constrict.

**Pact Blade.** {@atkr m} {@hit 10}, reach 5 ft. {@h}10 ({@damage 1d10 + 5}) Slashing damage plus 7 ({@damage 2d6}) Necrotic damage.

**Constrict.** {@actSave str} {@dc 17}, one Medium or smaller creature the marilith can see within 5 feet. {@actSaveFail} 15 ({@damage 2d10 + 4}) Bludgeoning damage. The target has the {@condition Grappled|XPHB} condition (escape {@dc 14}), and it has the {@condition Restrained|XPHB} condition until the grapple ends.

^Tags: #monster #type_unknown