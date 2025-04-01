# Young Copper Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Copper Dragon | Unknown | 7 | 119 (14d10 + 42) | 17 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 4 | - | - |
| Acid Breath {@recharge 5} | 9d8 | 14 | Half Damage ✅ |
| Slowing Breath | - | 14 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Slowing Breath.

**Rend.** {@atkr m} {@hit 7}, reach 10 ft. {@h}15 ({@damage 2d10 + 4}) Slashing damage.

**Acid Breath {@recharge 5}.** {@actSave dex} {@dc 14}, each creature in a 40-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 40 ({@damage 9d8}) Acid damage. {@actSaveSuccess} Half damage.

**Slowing Breath.** {@actSave con} {@dc 14}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target can't take Reactions; its {@variantrule Speed|XPHB} is halved; and it can take either an action or a {@variantrule Bonus Action|XPHB} on its turn, not both. This effect lasts until the end of its next turn.

^Tags: #monster #type_unknown