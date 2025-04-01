# Fomorian

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Fomorian | Giant | 8 | 172 (15d12 + 75) | 14 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Stone Club | 4d8 + 6 | - | - |
| Warping Hex {@recharge 4} | 6d6 | 16 | Half Damage ✅ |


**Multiattack.** The fomorian makes two Stone Club attacks. It can replace one attack with a use of Warping Hex if available.

**Stone Club.** {@atkr m} {@hit 9}, reach 15 ft. {@h}24 ({@damage 4d8 + 6}) Bludgeoning damage.

**Warping Hex {@recharge 4}.** {@actSave wis} {@dc 16}, one creature the fomorian can see within 120 feet. {@actSaveFail} 21 ({@damage 6d6}) Psychic damage, and the target gains 1 {@condition Exhaustion|XPHB} level. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_giant