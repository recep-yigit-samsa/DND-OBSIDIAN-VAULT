# Mummy Lord

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mummy Lord | Unknown | {'cr': '15', 'xpLair': 15000} | 187 (25d8 + 75) | 17 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rotting Fist | 2d10 + 4 + 3d6 | - | - |
| Channel Negative Energy | 6d6 + 4 | - | - |
| Dreadful Glare | 6d6 + 4 | 17 | - |


**Multiattack.** The mummy makes one Rotting Fist or Channel Negative Energy attack, and it uses Dreadful Glare.

**Rotting Fist.** {@atkr m} {@hit 9}, reach 5 ft. {@h}15 ({@damage 2d10 + 4}) Bludgeoning damage plus 10 ({@damage 3d6}) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can't regain {@variantrule Hit Points|XPHB}, it gains no benefit from finishing a {@variantrule Long Rest|XPHB}, and its {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by 10 ({@dice 3d6}) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 {@variantrule Hit Points|XPHB} by this attack.

**Channel Negative Energy.** {@atkr r} {@hit 9}, range 60 ft. {@h}25 ({@damage 6d6 + 4}) Necrotic damage.

**Dreadful Glare.** {@actSave wis} {@dc 17}, one creature the mummy can see within 60 feet. {@actSaveFail} 25 ({@damage 6d6 + 4}) Psychic damage, and the target has the {@condition Paralyzed|XPHB} condition until the end of the mummy's next turn.

^Tags: #monster #type_unknown