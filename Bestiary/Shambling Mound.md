# Shambling Mound

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shambling Mound | Plant | 5 | 110 (13d10 + 39) | 15 | walk: 30 ft., swim: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Charged Tendril | 1d6 + 4 + 2d4 | - | - |
| Engulf | 3d6 | 15 | - |


**Multiattack.** The shambling mound makes three Charged Tendril attacks. It can replace one attack with a use of Engulf.

**Charged Tendril.** {@atkr m} {@hit 7}, reach 10 ft. {@h}7 ({@damage 1d6 + 4}) Bludgeoning damage plus 5 ({@damage 2d4}) Lightning damage. If the target is a Medium or smaller creature, the shambling mound pulls the target 5 feet straight toward itself.

**Engulf.** {@actSave str} {@dc 15}, one Medium or smaller creature within 5 feet. {@actSaveFail} The target is pulled into the shambling mound's space and has the {@condition Grappled|XPHB} condition (escape {@dc 14}). Until the grapple ends, the target has the {@condition Blinded|XPHB} and {@condition Restrained|XPHB} conditions, and it takes 10 ({@damage 3d6}) Lightning damage at the start of each of its turns. When the shambling mound moves, the {@condition Grappled|XPHB} target moves with it, costing it no extra movement. The shambling mound can have only one creature {@condition Grappled|XPHB} by this action at a time.

^Tags: #monster #type_plant