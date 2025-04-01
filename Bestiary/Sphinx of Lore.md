# Sphinx of Lore

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sphinx of Lore | Celestial | {'cr': '11', 'xpLair': 8400} | 170 (20d10 + 60) | 17 | walk: 40 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 3d6 + 4 | - | - |
| Mind-Rending Roar {@recharge 5} | 10d6 | 16 | - |


**Multiattack.** The sphinx makes three Claw attacks.

**Claw.** {@atkr m} {@hit 8}, reach 5 ft. {@h}14 ({@damage 3d6 + 4}) Slashing damage.

**Mind-Rending Roar {@recharge 5}.** {@actSave wis} {@dc 16}, each enemy in a 300-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the sphinx. {@actSaveFail} 35 ({@damage 10d6}) Psychic damage, and the target has the {@condition Incapacitated|XPHB} condition until the start of the sphinx's next turn.

^Tags: #monster #type_celestial