# Ghost

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ghost | Undead | 4 | 45 (10d8) | 11 | walk: 5 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Withering Touch | 3d10 + 3 | - | - |
| Horrific Visage | 2d6 + 3 | 13 | - |
| Possession {@recharge} | - | 13 | - |


**Multiattack.** The ghost makes two Withering Touch attacks.

**Withering Touch.** {@atkr m} {@hit 5}, reach 5 ft. {@h}19 ({@damage 3d10 + 3}) Necrotic damage.

**Horrific Visage.** {@actSave wis} {@dc 13}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone} that can see the ghost and isn't an Undead. {@actSaveFail} 10 ({@damage 2d6 + 3}) Psychic damage, and the target has the {@condition Frightened|XPHB} condition until the start of the ghost's next turn. {@actSaveSuccess} The target is immune to this ghost's Horrific Visage for 24 hours.

**Possession {@recharge}.** {@actSave cha} {@dc 13}, one Humanoid the ghost can see within 5 feet. {@actSaveFail} The target is possessed by the ghost; the ghost disappears, and the target has the {@condition Incapacitated|XPHB} condition and loses control of its body. The ghost now controls the body, but the target retains awareness. The ghost can't be targeted by any attack, spell, or other effect, except ones that specifically target Undead. The ghost's game statistics are the same, except it uses the possessed target's {@variantrule Speed|XPHB}, as well as the target's Strength, Dexterity, and Constitution modifiers. The possession lasts until the body drops to 0 {@variantrule Hit Points|XPHB} or the ghost leaves as a {@variantrule Bonus Action|XPHB}. When the possession ends, the ghost appears in an unoccupied space within 5 feet of the target, and the target is immune to this ghost's {@variantrule Possession|XPHB} for 24 hours. {@actSaveSuccess} The target is immune to this ghost's {@variantrule Possession|XPHB} for 24 hours.

^Tags: #monster #type_undead