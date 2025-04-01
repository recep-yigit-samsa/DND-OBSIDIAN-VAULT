# Sea Hag

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Sea Hag | Fey | 2 | 52 (7d8 + 21) | 14 | walk: 30 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Claw | 2d6 + 3 | - | - |
| Death Glare {@recharge 5} | 3d8 | 11 | - |


**Claw.** {@atkr m} {@hit 5}, reach 5 ft. {@h}10 ({@damage 2d6 + 3}) Slashing damage.

**Death Glare {@recharge 5}.** {@actSave wis} {@dc 11}, one {@condition Frightened|XPHB} creature the hag can see within 30 feet. {@actSaveFail} If the target has 20 {@variantrule Hit Points|XPHB} or fewer, it drops to 0 {@variantrule Hit Points|XPHB}. Otherwise, the target takes 13 ({@damage 3d8}) Psychic damage.

^Tags: #monster #type_fey