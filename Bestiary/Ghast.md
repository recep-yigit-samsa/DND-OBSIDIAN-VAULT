# Ghast

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ghast | Undead | 2 | 36 (8d8) | 13 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 1d8 + 3 + 2d8 | - | - |
| Claw | 2d6 + 3 | 10 | - |


**Bite.** {@atkr m} {@hit 5}, reach 5 ft. {@h}7 ({@damage 1d8 + 3}) Piercing damage plus 9 ({@damage 2d8}) Necrotic damage.

**Claw.** {@atkr m} {@hit 5}, reach 5 ft. {@h}10 ({@damage 2d6 + 3}) Slashing damage. If the target is a non-Undead creature, it is subjected to the following effect. {@actSave con} {@dc 10}. {@actSaveFail} The target has the {@condition Paralyzed|XPHB} condition until the end of its next turn.

^Tags: #monster #type_undead