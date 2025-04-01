# Gladiator

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gladiator | Humanoid | 5 | 112 (15d8 + 45) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Spear | 2d6 + 4 | - | - |
| Shield Bash | 2d4 + 4 | 15 | - |


**Multiattack.** The gladiator makes three Spear attacks. It can replace one attack with a use of Shield Bash.

**Spear.** {@atkr m,r} {@hit 7}, reach 5 ft. or range 20/60 ft. {@h}11 ({@damage 2d6 + 4}) Piercing damage.

**Shield Bash.** {@actSave str} {@dc 15}, one creature within 5 feet that the gladiator can see. {@actSaveFail} 9 ({@damage 2d4 + 4}) Bludgeoning damage. If the target is a Medium or smaller creature, it has the {@condition Prone|XPHB} condition.

^Tags: #monster #type_humanoid