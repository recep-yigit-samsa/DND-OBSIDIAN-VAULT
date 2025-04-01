# Ghoul

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ghoul | Undead | 1 | 22 (5d8) | 12 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 2 + 1d6 | - | - |
| Claw | 1d4 + 2 | 10 | - |


**Multiattack.** The ghoul makes two Bite attacks.

**Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}5 ({@damage 1d6 + 2}) Piercing damage plus 3 ({@damage 1d6}) Necrotic damage.

**Claw.** {@atkr m} {@hit 4}, reach 5 ft. {@h}4 ({@damage 1d4 + 2}) Slashing damage. If the target is a creature that isn't an Undead or elf, it is subjected to the following effect. {@actSave con} {@dc 10}. {@actSaveFail} The target has the {@condition Paralyzed|XPHB} condition until the end of its next turn.

^Tags: #monster #type_undead