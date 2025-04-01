# Young Blue Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Blue Dragon | Unknown | 9 | 152 (16d10 + 64) | 18 | walk: 40 ft., burrow: 20 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d6 + 5 + 1d10 | - | - |
| Lightning Breath {@recharge 5} | 10d10 | 16 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atkr m} {@hit 9}, reach 10 ft. {@h}12 ({@damage 2d6 + 5}) Slashing damage plus 5 ({@damage 1d10}) Lightning damage.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 16}, each creature in a 60-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 55 ({@damage 10d10}) Lightning damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown