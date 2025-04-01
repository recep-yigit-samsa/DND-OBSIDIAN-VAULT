# Spy Master

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Spy Master | Humanoid | 10 | 137 (25d8 + 25) | 19 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rapier | 2d8 + 5 + 2d6 | - | - |
| Hand Crossbow | 2d6 + 5 + 2d8 | - | - |
| Smoke Bomb (1/Day) | 8d6 | 16 | Half Damage ✅ |


**Multiattack.** The spy makes three attacks, using Rapier or Hand Crossbow in any combination.

**Rapier.** {@atkr m} {@hit 9}, reach 5 ft. {@h}14 ({@damage 2d8 + 5}) Piercing damage plus 7 ({@damage 2d6}) Poison damage.

**Hand Crossbow.** {@atkr r} {@hit 9}, range 30/120 ft. {@h}12 ({@damage 2d6 + 5}) Piercing damage plus 9 ({@damage 2d8}) Poison damage.

**Smoke Bomb (1/Day).** The spy throws a bomb to a point it can see within 30 feet of itself. {@actSave con} {@dc 16}, each creature in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on that point. {@actSaveFail} 28 ({@damage 8d6}) Poison damage, and the target has the {@condition Blinded|XPHB} condition until the end of the spy's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_humanoid