# Mind Flayer Arcanist

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mind Flayer Arcanist | Aberration | 11 | 143 (26d8 + 26) | 16 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Arcane Tentacles | 4d10 + 5 | - | - |
| Mind Burst {@recharge 5} | 8d8 + 5 | 17 | Half Damage ✅ |


**Multiattack.** The mind flayer makes three Arcane Tentacles attacks.

**Arcane Tentacles.** {@atkr m,r} {@hit 9}, reach 5 ft. or range 120 ft. {@h}27 ({@damage 4d10 + 5}) Psychic damage, and the mind flayer can teleport the target up to 30 feet to an unoccupied space the mind flayer can see on a surface or liquid large enough to support the target. If this damage reduces the target to 0 {@variantrule Hit Points|XPHB}, the mind flayer kills it and magically devours its brain.

**Mind Burst {@recharge 5}.** {@actSave int} {@dc 17}, each creature in a 40-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the mind flayer. {@actSaveFail} 41 ({@damage 8d8 + 5}) Psychic damage, and the target has the {@condition Stunned|XPHB} condition until the end of the mind flayer's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_aberration