# Adult Red Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Red Dragon | Unknown | {'cr': '17', 'xpLair': 20000} | 256 (19d12 + 133) | 19 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d10 + 8 + 2d4 | - | - |
| Fire Breath {@recharge 5} | 17d6 | 21 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast {@spell Scorching Ray|XPHB}.

**Rend.** {@atkr m} {@hit 14}, reach 10 ft. {@h}13 ({@damage 1d10 + 8}) Slashing damage plus 5 ({@damage 2d4}) Fire damage.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 21}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 59 ({@damage 17d6}) Fire damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown