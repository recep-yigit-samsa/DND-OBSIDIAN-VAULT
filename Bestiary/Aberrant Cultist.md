# Aberrant Cultist

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Aberrant Cultist | Humanoid | 8 | 137 (25d8 + 25) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle Lash | 1d6 + 4 + 4d6 | 14 | - |
| Mind Rot | 6d8 | 15 | Half Damage ✅ |


**Multiattack.** The cultist makes two Tentacle Lash attacks. It can replace any attack with a use of Mind Rot.

**Tentacle Lash.** {@atkr m} {@hit 7}, reach 10 ft. {@h}7 ({@damage 1d6 + 4}) Slashing damage plus 14 ({@damage 4d6}) Psychic damage. If the target is a Large or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 14}) from one of two tentacles, and it has the {@condition Restrained|XPHB} condition until the grapple ends.

**Mind Rot.** {@actSave wis} {@dc 15}, one creature the cultist can see within 90 feet. {@actSaveFail} 27 ({@damage 6d8}) Psychic damage, and the target has the {@condition Poisoned|XPHB} condition until the start of the cultist's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_humanoid