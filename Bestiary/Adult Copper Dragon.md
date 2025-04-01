# Adult Copper Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Copper Dragon | Unknown | {'cr': '14', 'xpLair': 13000} | 184 (16d12 + 80) | 18 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 6 + 1d8 | - | - |
| Acid Breath {@recharge 5} | 12d8 | 18 | Half Damage ✅ |
| Slowing Breath | - | 18 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Slowing Breath or (B) Spellcasting to cast {@spell Mind Spike|XPHB} (level 4 version).

**Rend.** {@atkr m} {@hit 11}, reach 10 ft. {@h}17 ({@damage 2d10 + 6}) Slashing damage plus 4 ({@damage 1d8}) Acid damage.

**Acid Breath {@recharge 5}.** {@actSave dex} {@dc 18}, each creature in an 60-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 54 ({@damage 12d8}) Acid damage. {@actSaveSuccess} Half damage.

**Slowing Breath.** {@actSave con} {@dc 18}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target can't take Reactions; its {@variantrule Speed|XPHB} is halved; and it can take either an action or a {@variantrule Bonus Action|XPHB} on its turn, not both. This effect lasts until the end of its next turn.

^Tags: #monster #type_unknown