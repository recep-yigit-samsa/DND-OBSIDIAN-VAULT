# Adult Blue Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Blue Dragon | Unknown | {'cr': '16', 'xpLair': 18000} | 212 (17d12 + 102) | 19 | walk: 40 ft., burrow: 30 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d8 + 7 + 1d10 | - | - |
| Lightning Breath {@recharge 5} | 11d10 | 19 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Shatter|XPHB}.

**Rend.** {@atkr m} {@hit 12}, reach 10 ft. {@h}16 ({@damage 2d8 + 7}) Slashing damage plus 5 ({@damage 1d10}) Lightning damage.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 19}, each creature in a 90-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 60 ({@damage 11d10}) Lightning damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown