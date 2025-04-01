# Bronze Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bronze Dragon Wyrmling | Unknown | 2 | 39 (6d8 + 12) | 15 | walk: 30 ft., fly: 60 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d10 + 3 | - | - |
| Lightning Breath {@recharge 5} | 3d10 | 12 | Half Damage ✅ |
| Repulsion Breath | - | 12 | - |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 5}, reach 5 ft. {@h}8 ({@damage 1d10 + 3}) Slashing damage.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 12}, each creature in a 40-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 16 ({@damage 3d10}) Lightning damage. {@actSaveSuccess} Half damage.

**Repulsion Breath.** {@actSave str} {@dc 12}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target is pushed up to 30 feet straight away from the dragon and has the {@condition Prone|XPHB} condition.

^Tags: #monster #type_unknown