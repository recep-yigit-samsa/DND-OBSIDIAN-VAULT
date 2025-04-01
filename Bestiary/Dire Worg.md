# Dire Worg

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dire Worg | Fey | 10 | 147 (14d12 + 56) | 16 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d8 + 6 + 2d6 | - | - |
| Dreadful Howl {@recharge 5} | 8d8 | 16 | Half Damage ✅ |


**Multiattack.** The worg makes three Bite attacks.

**Bite.** {@atkr m} {@hit 10}, reach 5 ft. {@h}15 ({@damage 2d8 + 6}) Piercing damage plus 7 ({@damage 2d6}) Poison damage, and the target has the {@condition Poisoned|XPHB} condition until the start of the worg's next turn. While {@condition Poisoned|XPHB}, the target can't regain {@variantrule Hit Points|XPHB}.

**Dreadful Howl {@recharge 5}.** {@actSave wis} {@dc 16}, each creature within 30 feet that isn't a worg. {@actSaveFail} 36 ({@damage 8d8}) Psychic damage, and the target has the {@condition Frightened|XPHB} condition until the start of the worg's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_fey