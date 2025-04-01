# Lamia

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lamia | Fiend | 4 | 97 (13d10 + 26) | 13 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 1d8 + 3 + 2d6 | - | - |
| Corrupting Touch | 3d8 | 13 | - |


**Multiattack.** The lamia makes two Claw attacks. It can replace one attack with a use of Corrupting Touch.

**Claw.** {@atkr m} {@hit 5}, reach 5 ft. {@h}7 ({@damage 1d8 + 3}) Slashing damage plus 7 ({@damage 2d6}) Psychic damage.

**Corrupting Touch.** {@actSave wis} {@dc 13}, one creature the lamia can see within 5 feet. {@actSaveFail} 13 ({@damage 3d8}) Psychic damage, and the target is cursed for 1 hour. Until the curse ends, the target has the {@condition Charmed|XPHB} and {@condition Poisoned|XPHB} conditions.

^Tags: #monster #type_fiend