# Banshee

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Banshee | Undead | 4 | 54 (12d8) | 12 | walk: 5 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Corrupting Touch | 1d8 + 3 | - | - |
| Horrify | - | 13 | - |
| Deathly Wail (1/Day) | 3d6 | 13 | - |


**Multiattack.** The banshee makes two Corrupting Touch attacks and uses Horrify.

**Corrupting Touch.** {@atkr m} {@hit 5}, reach 5 ft. {@h}7 ({@damage 1d8 + 3}) Necrotic damage.

**Horrify.** {@actSave wis} {@dc 13}, one creature the banshee can see within 60 feet that can see the banshee. {@actSaveFail} The target has the {@condition Frightened|XPHB} condition until the start of the banshee's next turn. {@actSaveSuccess} The target is immune to this banshee's Horrify for 24 hours.

**Deathly Wail (1/Day).** The banshee releases a mournful wail if it isn't in sunlight. {@actSave con} {@dc 13}, each creature within 30 feet that can hear the wail and isn't a Construct or an Undead. {@actSaveFail} If the target has 25 {@variantrule Hit Points|XPHB} or fewer, it drops to 0 {@variantrule Hit Points|XPHB}. Otherwise, the target takes 10 ({@damage 3d6}) Psychic damage.

^Tags: #monster #type_undead