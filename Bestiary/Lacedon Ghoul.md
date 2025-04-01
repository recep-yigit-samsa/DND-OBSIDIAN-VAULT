# Lacedon Ghoul

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lacedon Ghoul | Undead | 1 | 22 (5d8) | 12 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Icy Bite | 2d6 + 2 | - | - |
| Claw | 1d4 + 2 | 10 | - |


**Multiattack.** The ghoul makes two Icy Bite attacks.

**Icy Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}9 ({@damage 2d6 + 2}) Cold damage, and the target's {@variantrule Speed|XPHB} decreases by 5 feet until the start of the ghoul's next turn.

**Claw.** {@atkr m} {@hit 4}, reach 5 ft. {@h}4 ({@damage 1d4 + 2}) Slashing damage. If the target is a creature that isn't an Undead or elf, it is subjected to the following effect. {@actSave con} {@dc 10}. {@actSaveFail} The target has the {@condition Paralyzed|XPHB} condition until the end of its next turn.

^Tags: #monster #type_undead