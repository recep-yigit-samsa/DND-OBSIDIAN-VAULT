# Ultroloth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ultroloth | Unknown | 13 | 221 (26d8 + 104) | 19 | walk: 30 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Mercurial Whip | 6d6 + 4 | - | - |
| Hypnotic Gaze | 3d6 | 17 | - |


**Multiattack.** The ultroloth uses Hypnotic Gaze and makes two Mercurial Whip attacks.

**Mercurial Whip.** {@atkr m} {@hit 9}, reach 15 ft. {@h}25 ({@damage 6d6 + 4}) Force damage, and the ultroloth can teleport the target up to 10 feet to an unoccupied space the ultroloth can see that isn't in the air.

**Hypnotic Gaze.** {@actSave wis} {@dc 17}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 10 ({@damage 3d6}) Psychic damage, and the target has the {@condition Stunned|XPHB} condition until the start of the ultroloth's next turn. {@actSaveSuccess} The target is immune to this ultroloth's Hypnotic Gaze for 24 hours.

^Tags: #monster #type_unknown