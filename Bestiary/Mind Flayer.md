# Mind Flayer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mind Flayer | Aberration | 7 | 99 (18d8 + 18) | 15 | walk: 30 ft., fly: {'number': 15, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tentacles | 4d8 + 4 | 14 | - |
| Extract Brain | 10d10 | 15 | Half Damage ✅ |
| Mind Blast {@recharge 5} | 6d8 + 4 | 15 | Half Damage ✅ |


**Tentacles.** {@atkr m} {@hit 7}, reach 5 ft. {@h}22 ({@damage 4d8 + 4}) Psychic damage. If the target is a Medium or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 14}) from all the mind flayer's tentacles, and the target has the {@condition Stunned|XPHB} condition until the grapple ends.

**Extract Brain.** {@actSave con} {@dc 15}, one creature that is {@condition Grappled|XPHB} by the mind flayer's Tentacles. {@actSaveFail} 55 ({@damage 10d10}) Piercing damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} If this damage reduces the target to 0 {@variantrule Hit Points|XPHB}, the mind flayer kills it and devours its brain.

**Mind Blast {@recharge 5}.** {@actSave int} {@dc 15}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 31 ({@damage 6d8 + 4}) Psychic damage, and the target has the {@condition Stunned|XPHB} condition until the end of the mind flayer's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_aberration