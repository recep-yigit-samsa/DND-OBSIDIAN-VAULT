# Behir

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Behir | Monstrosity | 11 | 168 (16d12 + 64) | 17 | walk: 50 ft., climb: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 6 + 2d10 | - | - |
| Constrict | 5d8 + 6 | 18 | - |
| Lightning Breath {@recharge 5} | 12d10 | 16 | Half Damage ✅ |


**Multiattack.** The behir makes one Bite attack and uses Constrict.

**Bite.** {@atkr m} {@hit 10}, reach 10 ft. {@h}19 ({@damage 2d12 + 6}) Piercing damage plus 11 ({@damage 2d10}) Lightning damage.

**Constrict.** {@actSave str} {@dc 18}, one Large or smaller creature the behir can see within 5 feet. {@actSaveFail} 28 ({@damage 5d8 + 6}) Bludgeoning damage. The target has the {@condition Grappled|XPHB} condition (escape {@dc 16}), and it has the {@condition Restrained|XPHB} condition until the grapple ends.

**Lightning Breath {@recharge 5}.** {@actSave dex} {@dc 16}, each creature in a 90-foot-long, 5-foot-wide {@variantrule Line [Area of Effect]|XPHB|Line}. {@actSaveFail} 66 ({@damage 12d10}) Lightning damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_monstrosity