# Pseudodragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Pseudodragon | Dragon | 1/4 | 10 (3d4 + 3) | 14 | walk: 15 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d4 + 2 | - | - |
| Sting | 2d4 | 12 | - |


**Multiattack.** The pseudodragon makes two Bite attacks.

**Bite.** {@atkr m} {@hit 4}, reach 5 ft. {@h}4 ({@damage 1d4 + 2}) Piercing damage.

**Sting.** {@actSave con} {@dc 12}, one creature the pseudodragon can see within 5 feet. {@actSaveFail} 5 ({@damage 2d4}) Poison damage, and the target has the {@condition Poisoned|XPHB} condition for 1 hour. Failure by 5 or More: The {@condition Poisoned|XPHB} target also has the {@condition Unconscious|XPHB} condition until it takes damage or a creature within 5 feet of it takes an action to shake it awake.

^Tags: #monster #type_dragon