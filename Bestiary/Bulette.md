# Bulette

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bulette | Monstrosity | 5 | 94 (9d10 + 45) | 17 | walk: 40 ft., burrow: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 4 | - | - |
| Deadly Leap | 3d12 | 15 | Half Damage ✅ |


**Multiattack.** The bulette makes two Bite attacks.

**Bite.** {@atkr m} {@hit 7}, reach 5 ft. {@h}17 ({@damage 2d12 + 4}) Piercing damage.

**Deadly Leap.** The bulette spends 5 feet of movement to jump to a space within 15 feet that contains one or more Large or smaller creatures. {@actSave dex} {@dc 15}, each creature in the bulette's destination space. {@actSaveFail} 19 ({@damage 3d12}) Bludgeoning damage, and the target has the {@condition Prone|XPHB} condition. {@actSaveSuccess} Half damage, and the target is pushed 5 feet straight away from the bulette.

^Tags: #monster #type_monstrosity