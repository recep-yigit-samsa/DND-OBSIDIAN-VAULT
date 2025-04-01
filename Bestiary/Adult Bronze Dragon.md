# Adult Bronze Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Bronze Dragon | Unknown | {'cr': '15', 'xpLair': 15000} | 212 (17d12 + 102) | 18 | walk: 40 ft., fly: 80 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 7 + 1d10 | - | - |
| Lightning Breath {@recharge 5} | 10d10 | 19 | Half Damage ✅ |
| Repulsion Breath | - | 19 | - |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Repulsion Breath or (B) Spellcasting to cast {@spell Guiding Bolt|XPHB} (level 2 version).

**Rend.** {@atkr m} {@hit 12}, reach 10 ft. {@h}16 ({@damage 2d8 + 7}) Slashing damage plus 5 ({@damage 1d10}) Lightning damage.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 19}, each creature in a 90-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 55 ({@damage 10d10}) Lightning damage. {@actSaveSuccess} Half damage.

**Repulsion Breath.** {@actSave str} {@dc 19}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target is pushed up to 60 feet straight away from the dragon and has the {@condition Prone|XPHB} condition.

^Tags: #monster #type_unknown