# Marid

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Marid | Unknown | 11 | 229 (17d10 + 136) | 17 | walk: 30 ft., fly: 60 ft., swim: 90 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Aquatic Lash | 2d8 + 6 + 2d8 | - | - |
| Water Jet | 9d6 | 18 | Half Damage ✅ |


**Multiattack.** The marid makes three Aquatic Lash attacks.

**Aquatic Lash.** {@atkr m} {@hit 10}, reach 15 ft. {@h}15 ({@damage 2d8 + 6}) Slashing damage plus 9 ({@damage 2d8}) Cold damage.

**Water Jet.** {@actSave dex} {@dc 18}, each creature in a 60-foot-long, 10-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 31 ({@damage 9d6}) Cold damage. If the target is a Huge or smaller creature, it is pushed up to 20 feet straight away from the marid and has the {@condition Prone|XPHB} condition. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_unknown