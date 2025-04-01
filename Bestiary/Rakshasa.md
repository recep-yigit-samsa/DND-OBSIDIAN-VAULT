# Rakshasa

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Rakshasa | Fiend | 13 | 221 (26d8 + 104) | 17 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Cursed Touch | 2d6 + 5 + 3d12 | - | - |
| Baleful Command {@recharge 5} | 8d6 | 18 | - |


**Multiattack.** The rakshasa makes three Cursed Touch attacks.

**Cursed Touch.** {@atkr m} {@hit 10}, reach 5 ft. {@h}12 ({@damage 2d6 + 5}) Slashing damage plus 19 ({@damage 3d12}) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target gains no benefit from finishing a {@variantrule Short Rest|XPHB|Short} or {@variantrule Long Rest|XPHB}.

**Baleful Command {@recharge 5}.** {@actSave wis} {@dc 18}, each enemy in a 30-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the rakshasa. {@actSaveFail} 28 ({@damage 8d6}) Psychic damage, and the target has the {@condition Frightened|XPHB} and {@condition Incapacitated|XPHB} conditions until the start of the rakshasa's next turn.

^Tags: #monster #type_fiend