# Young Bronze Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Bronze Dragon | Unknown | 8 | 142 (15d10 + 60) | 17 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 5 | - | - |
| Lightning Breath {@recharge 5} | 9d10 | 15 | Half Damage ✅ |
| Repulsion Breath | - | 15 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Repulsion Breath.

**Rend.** {@atkr m} {@hit 8}, reach 10 ft. {@h}16 ({@damage 2d10 + 5}) Slashing damage.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 15}, each creature in a 60-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 49 ({@damage 9d10}) Lightning damage. {@actSaveSuccess} Half damage.

**Repulsion Breath.** {@actSave str} {@dc 15}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target is pushed up to 40 feet straight away from the dragon and has the {@condition Prone|XPHB} condition.

^Tags: #monster #type_unknown