# Colossus

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Colossus | Unknown | 25 | 553 (27d20 + 270) | 23 | walk: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d10 + 10 | - | - |
| Radiant Ray | 4d10 | - | - |
| Divine Beam {@recharge 5} | 10d12 | 26 | Half Damage ✅ |


**Multiattack.** The colossus makes three attacks, using Slam or Radiant Ray in any combination.

**Slam.** {@atkr m} {@hit 18}, reach 20 ft. {@h}32 ({@damage 4d10 + 10}) Bludgeoning damage, and the colossus pushes the target up to 20 feet straight away from itself.

**Radiant Ray.** {@atkr r} {@hit 18}, range 300 ft. {@h}22 ({@damage 4d10}) Radiant damage. If the target is a Large or smaller creature, it has the {@condition Prone|XPHB} condition.

**Divine Beam {@recharge 5}.** {@actSave dex} {@dc 26}, each creature in a 300-foot-long, 10-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 65 ({@damage 10d12}) Radiant damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} A creature reduced to 0 {@variantrule Hit Points|XPHB} by this beam disintegrates into dust, leaving behind any magic items it was wearing or carrying.

^Tags: #monster #type_unknown