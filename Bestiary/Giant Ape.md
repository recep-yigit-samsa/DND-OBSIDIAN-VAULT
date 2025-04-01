# Giant Ape

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Giant Ape | Beast | 7 | 168 (16d12 + 64) | 12 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Fist | 3d10 + 6 | - | - |
| Boulder Toss {@recharge} | 7d6 | 17 | Half Damage ✅ |


**Multiattack.** The ape makes two Fist attacks.

**Fist.** {@atkr m} {@hit 9}, reach 10 ft. {@h}22 ({@damage 3d10 + 6}) Bludgeoning damage.

**Boulder Toss {@recharge}.** The ape hurls a boulder at a point it can see within 90 feet. {@actSave dex} {@dc 17}, each creature in a 5-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on that point. {@actSaveFail} 24 ({@damage 7d6}) Bludgeoning damage. If the target is a Large or smaller creature, it has the {@condition Prone|XPHB} condition. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_beast