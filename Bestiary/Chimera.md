# Chimera

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Chimera | Monstrosity | 6 | 114 (12d10 + 48) | 14 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 4 + 4d6 + 4 | - | - |
| Claw | 1d6 + 4 | - | - |
| Ram | 1d12 + 4 | - | - |
| Fire Breath {@recharge 5} | 7d8 | 15 | Half Damage ✅ |


**Multiattack.** The chimera makes one Ram attack, one Bite attack, and one Claw attack. It can replace the Claw attack with a use of Fire Breath if available.

**Bite.** {@atkr m} {@hit 7}, reach 5 ft. {@h}11 ({@damage 2d6 + 4}) Piercing damage, or 18 ({@damage 4d6 + 4}) Piercing damage if the chimera had {@variantrule Advantage|XPHB} on the attack roll.

**Claw.** {@atkr m} {@hit 7}, reach 5 ft. {@h}7 ({@damage 1d6 + 4}) Slashing damage.

**Ram.** {@atkr m} {@hit 7}, reach 5 ft. {@h}10 ({@damage 1d12 + 4}) Bludgeoning damage. If the target is a Medium or smaller creature, it has the {@condition Prone|XPHB} condition.

**Fire Breath {@recharge 5}.** {@actSave dex} {@dc 15}, each creature in a 15-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 31 ({@damage 7d8}) Fire damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_monstrosity