# Lizardfolk Geomancer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Lizardfolk Geomancer | Elemental | 2 | 33 (6d8 + 6) | 13 | walk: 30 ft., burrow: 20 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Earth Burst | 2d6 + 2 | - | - |
| Hail of Stone {@recharge 5} | 6d4 | 12 | Half Damage ✅ |


**Multiattack.** The lizardfolk makes two Earth Burst attacks.

**Earth Burst.** {@atkr m,r} {@hit 4}, reach 5 ft. or range 60 ft. {@h}9 ({@damage 2d6 + 2}) Bludgeoning damage.

**Hail of Stone {@recharge 5}.** {@actSave con} {@dc 12}, each creature in a 20-foot-radius, 40-foot-high {@variantrule Cylinder [Area of Effect]|XPHB|Cylinder} centered on a point the lizardfolk can see within 60 feet. {@actSaveFail} 15 ({@damage 6d4}) Bludgeoning damage, and the target has the {@condition Prone|XPHB} condition. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_elemental