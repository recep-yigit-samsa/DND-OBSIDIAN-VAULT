# Mummy

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mummy | Undead | 3 | 58 (9d8 + 18) | 11 | walk: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rotting Fist | 1d10 + 3 + 3d6 | - | - |
| Dreadful Glare | - | 11 | - |


**Multiattack.** The mummy makes two Rotting Fist attacks and uses Dreadful Glare.

**Rotting Fist.** {@atkr m} {@hit 5}, reach 5 ft. {@h}8 ({@damage 1d10 + 3}) Bludgeoning damage plus 10 ({@damage 3d6}) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can't regain {@variantrule Hit Points|XPHB}, its {@variantrule Hit Points|XPHB|Hit Point} maximum doesn't return to normal when finishing a {@variantrule Long Rest|XPHB}, and its {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by 10 ({@dice 3d6}) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 {@variantrule Hit Points|XPHB} by this attack.

**Dreadful Glare.** {@actSave wis} {@dc 11}, one creature the mummy can see within 60 feet. {@actSaveFail} The target has the {@condition Frightened|XPHB} condition until the end of the mummy's next turn. {@actSaveSuccess} The target is immune to this mummy's Dreadful Glare for 24 hours.

^Tags: #monster #type_undead