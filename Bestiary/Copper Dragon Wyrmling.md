# Copper Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Copper Dragon Wyrmling | Unknown | 1 | 22 (4d8 + 4) | 16 | walk: 30 ft., climb: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Rend | 1d10 + 2 | - | - |
| Acid Breath {@recharge 5} | 4d8 | 11 | Half Damage ✅ |
| Slowing Breath | - | 11 | - |


**Rend.** {@atkr m} {@hit 4}, reach 5 ft. {@h}7 ({@damage 1d10 + 2}) Slashing damage.

**Acid Breath {@recharge 5}.** {@actSave dex} {@dc 11}, each creature in a 20-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 18 ({@damage 4d8}) Acid damage. {@actSaveSuccess} Half damage.

**Slowing Breath.** {@actSave con} {@dc 11}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target can't take Reactions; its {@variantrule Speed|XPHB} is halved; and it can take either an action or a {@variantrule Bonus Action|XPHB} on its turn, not both. This effect lasts until the end of its next turn.

^Tags: #monster #type_unknown