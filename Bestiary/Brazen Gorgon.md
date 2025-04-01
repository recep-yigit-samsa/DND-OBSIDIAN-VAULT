# Brazen Gorgon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Brazen Gorgon | Construct | 9 | 161 (17d10 + 68) | 19 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Gore | 2d6 + 4 + 3d6 | - | - |
| Smelting Charge {@recharge 5} | 2d8 + 4 + 3d8 | 16 | - |


**Multiattack.** The gorgon makes two Gore attacks.

**Gore.** {@atkr m} {@hit 8}, reach 5 ft. {@h}11 ({@damage 2d6 + 4}) Piercing damage plus 10 ({@damage 3d6}) Fire damage.

**Smelting Charge {@recharge 5}.** The gorgon moves up to its {@variantrule Speed|XPHB} without provoking Opportunity Attacks and can move through the spaces of Medium or smaller creatures. Each time the gorgon enters a creature's space for the first time during this move, that target is subjected to the following effect. {@actSave dex} {@dc 16}. {@actSaveFail} 13 ({@damage 2d8 + 4}) Piercing damage plus 13 ({@damage 3d8}) Fire damage, and the target is pulled into the gorgon's space and has the {@condition Grappled|XPHB} condition (escape {@dc 14}); if the gorgon already has a creature {@condition Grappled|XPHB}, the target has the {@condition Prone|XPHB} condition instead. Until the grapple ends, the target has the {@condition Restrained|XPHB} condition. When the gorgon moves, the {@condition Grappled|XPHB} target moves with it, costing no extra movement.

^Tags: #monster #type_construct