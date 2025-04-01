# Demilich

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Demilich | Undead | {'cr': '18', 'xpLair': 22000} | 180 (72d4) | 20 | walk: 5 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Necrotic Burst | 7d6 | - | - |
| Howl {@recharge 5} | 20d6 | 19 | - |


**Multiattack.** The demilich makes three Necrotic Burst attacks.

**Necrotic Burst.** {@atkr m,r} {@hit 11}, reach 5 ft. or range 120 ft. {@h}24 ({@damage 7d6}) Necrotic damage.

**Howl {@recharge 5}.** {@actSave con} {@dc 19}, each creature in a 30-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the demilich. {@actSaveFail} 70 ({@damage 20d6}) Psychic damage. {@actSaveSuccessOrFail} The target has the {@condition Frightened|XPHB} condition until the start of the demilich's next turn.

^Tags: #monster #type_undead