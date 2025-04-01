# Derro Apprentice

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Derro Apprentice | Aberration | 1 | 22 (5d6 + 5) | 13 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Chaos Blast | 3d6 | - | - |
| Force Burst {@recharge 4} | 2d6 | 11 | - |


**Chaos Blast.** {@atk ms,rs} {@hit 3} to hit, reach 5 ft. or range 60 ft., one target. {@h}10 ({@damage 3d6}) damage. Roll a {@dice d4} to determine the damage type: 1, acid; 2, cold; 3, fire; 4, lightning.

**Force Burst {@recharge 4}.** Raw arcane magic bursts out from the derro. Each creature within 10 feet of it must make a {@dc 11} Strength saving throw. On a failed save, the creature takes 7 ({@damage 2d6}) force damage and has the {@condition prone} condition. On a successful save, the creature takes half as much damage only.

^Tags: #monster #type_aberration