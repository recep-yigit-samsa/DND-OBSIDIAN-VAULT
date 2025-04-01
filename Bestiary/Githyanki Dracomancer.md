# Githyanki Dracomancer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Githyanki Dracomancer | Unknown | 16 | 255 (30d8 + 120) | 18 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Draconic Strike | 2d6 + 5 + 5d6 | - | - |
| Conjured Dragon's Breath {@recharge 5} | 6d8 + 6d8 | 18 | Half Damage ✅ |


**Multiattack.** The githyanki makes three Draconic Strike attacks.

**Draconic Strike.** {@atkr m,r} {@hit 10}, reach 10 ft. or range 120 ft. {@h}12 ({@damage 2d6 + 5}) Slashing damage plus 17 ({@damage 5d6}) Fire damage, and the target has the {@condition Frightened|XPHB} condition until the start of the githyanki's next turn.

**Conjured Dragon's Breath {@recharge 5}.** {@actSave dex} {@dc 18}, each creature in a 90-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 27 ({@damage 6d8}) Fire damage plus 27 ({@damage 6d8}) Force damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown