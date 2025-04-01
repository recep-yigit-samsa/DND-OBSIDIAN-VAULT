# Ancient Bronze Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Bronze Dragon | Unknown | {'cr': '22', 'xpLair': 50000} | 444 (24d20 + 192) | 22 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 9 + 2d8 | - | - |
| Lightning Breath {@recharge 5} | 15d10 | 23 | Half Damage ✅ |
| Repulsion Breath | - | 23 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Repulsion Breath or (B) Spellcasting to cast {@spell Guiding Bolt|XPHB} (level 2 version).

**Rend.** {@atkr m} {@hit 16}, reach 15 ft. {@h}18 ({@damage 2d8 + 9}) Slashing damage plus 9 ({@damage 2d8}) Lightning damage.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 23}, each creature in a 120-foot-long, 10-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 82 ({@damage 15d10}) Lightning damage. {@actSaveSuccess} Half damage.

**Repulsion Breath.** {@actSave str} {@dc 23}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target is pushed up to 60 feet straight away from the dragon and has the {@condition Prone|XPHB} condition.

^Tags: #monster #type_unknown