# Air Elemental

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Air Elemental | Elemental | 5 | 90 (12d10 + 24) | 15 | walk: 10 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Thunderous Slam | 2d8 + 5 | - | - |
| Whirlwind {@recharge 4} | 4d10 + 2 | 13 | Half Damage ✅ |


**Multiattack.** The elemental makes two Thunderous Slam attacks.

**Thunderous Slam.** {@atkr m} {@hit 8}, reach 10 ft. {@h}14 ({@damage 2d8 + 5}) Thunder damage.

**Whirlwind {@recharge 4}.** {@actSave str} {@dc 13}, one Medium or smaller creature in the elemental's space. {@actSaveFail} 24 ({@damage 4d10 + 2}) Thunder damage, and the target is pushed up to 20 feet straight away from the elemental and has the {@condition Prone|XPHB} condition. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_elemental