# Ramius

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ramius | Humanoid | 14 | 190 (20d8 + 100) | 22 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Longsword | 1d8 + 6 + 1d10 + 6 + 3d8 + 3d8 | 17 | - |
| Divine Wave {@recharge} | 6d6 + 6d6 | 17 | - |


**Multiattack.** Ramius makes two Longsword attacks.

**Longsword.** {@atk mw} {@hit 11} to hit, reach 5ft., one target. {@h}10 ({@damage 1d8 + 6}) slashing damage or 11 ({@damage 1d10 + 6}) if wielded in two hands, plus 13 ({@damage 3d8}) radiant damage. If the target is an evil creature, it must succeed on a {@dc 17} Charisma saving throw or take an additional 13 ({@damage 3d8}) radiant damage.

**Divine Wave {@recharge}.** Ramius strikes the ground and causes holy energy to radiate outwards. Each creature of his choice within 30 feet of him must make a {@dc 17} Constitution saving throw. Targets take 21 ({@damage 6d6}) thunder damage plus 21 ({@damage 6d6}) radiant damage on a failed save, or half as much damage on a successful one. Creatures that fail the save are knocked down (have the {@condition prone} condition).

^Tags: #monster #type_humanoid