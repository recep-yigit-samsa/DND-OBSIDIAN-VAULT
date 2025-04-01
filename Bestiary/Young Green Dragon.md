# Young Green Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Green Dragon | Unknown | 8 | 136 (16d10 + 48) | 18 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d6 + 4 + 2d6 | - | - |
| Poison Breath {@recharge 5} | 12d6 | 14 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atkr m} {@hit 7}, reach 10 ft. {@h}11 ({@damage 2d6 + 4}) Slashing damage plus 7 ({@damage 2d6}) Poison damage.

**Poison Breath {@recharge 5}.** {@actSave con} {@dc 14}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 42 ({@damage 12d6}) Poison damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown