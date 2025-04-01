# Flumph

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Flumph | Aberration | 1/8 | 7 (2d6) | 12 | walk: 5 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Tentacle | 1d4 + 2 | - | - |
| Stench Spray (1/Day) | - | 10 | - |


**Tentacle.** {@atkr m} {@hit 4}, reach 5 feet. {@h}4 ({@damage 1d4 + 2}) Acid damage.

**Stench Spray (1/Day).** {@actSave dex} {@dc 10}, one creature the flumph can see within 15 feet. {@actSaveFail} The target is coated in a foul-smelling liquid, exudes a stench for {@dice 1d4} hours, and has the {@condition Poisoned|XPHB} condition while the stench lasts. Other creatures have the {@condition Poisoned|XPHB} condition while in a 5-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the coated target. The target can remove the stench on itself if it bathes during a {@variantrule Short Rest|XPHB|Short} or {@variantrule Long Rest|XPHB}.

^Tags: #monster #type_aberration