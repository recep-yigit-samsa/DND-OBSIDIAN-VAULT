# Bandit Deceiver

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bandit Deceiver | Humanoid | 7 | 130 (20d8 + 40) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Dagger | 2d4 + 3 + 3d6 | - | - |
| Blinding Flash {@recharge 4} | 3d6 + 3 | 14 | Half Damage ✅ |


**Multiattack.** The bandit makes three Dagger attacks.

**Dagger.** {@atkr m,r} {@hit 6}, reach 5 ft. or range 20/60 ft. {@h}8 ({@damage 2d4 + 3}) Piercing damage plus 10 ({@damage 3d6}) Poison damage.

**Blinding Flash {@recharge 4}.** {@actSave con} {@dc 14}, each creature in a 10-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point the bandit can see within 120 feet. {@actSaveFail} 13 ({@damage 3d6 + 3}) Radiant damage, and the target has the {@condition Blinded|XPHB} condition until the start of the bandit's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_humanoid