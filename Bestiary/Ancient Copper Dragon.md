# Ancient Copper Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Copper Dragon | Unknown | {'cr': '21', 'xpLair': 41000} | 367 (21d20 + 147) | 21 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 8 + 2d8 | - | - |
| Acid Breath {@recharge 5} | 14d8 | 22 | Half Damage ✅ |
| Slowing Breath | - | 22 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Slowing Breath or (B) Spellcasting to cast {@spell Mind Spike|XPHB} (level 5 version).

**Rend.** {@atkr m} {@hit 15}, reach 15 ft. {@h}19 ({@damage 2d10 + 8}) Slashing damage plus 9 ({@damage 2d8}) Acid damage.

**Acid Breath {@recharge 5}.** {@actSave dex} {@dc 22}, each creature in an 90-foot-long, 10-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 63 ({@damage 14d8}) Acid damage. {@actSaveSuccess} Half damage.

**Slowing Breath.** {@actSave con} {@dc 22}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target can't take Reactions; its {@variantrule Speed|XPHB} is halved; and it can take either an action or a {@variantrule Bonus Action|XPHB} on its turn, not both. This effect lasts until the end of its next turn.

^Tags: #monster #type_unknown