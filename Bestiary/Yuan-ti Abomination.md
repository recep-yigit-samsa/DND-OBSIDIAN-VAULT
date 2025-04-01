# Yuan-ti Abomination

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Yuan-ti Abomination | Monstrosity | 7 | 127 (15d10 + 45) | 15 | walk: 40 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 4 + 3d6 | - | - |
| Constrict | 7d6 + 4 | 15 | Half Damage ✅ |
| Poison Spray {@recharge 5} | 6d6 | 14 | Half Damage ✅ |


**Multiattack.** The yuan-ti makes two Bite attacks, and it can use Spellcasting to cast {@spell Suggestion|XPHB} if available.

**Bite.** {@atkr m} {@hit 7}, reach 5 ft. {@h}11 ({@damage 2d6 + 4}) Piercing damage plus 10 ({@damage 3d6}) Poison damage.

**Constrict.** {@actSave str} {@dc 15}, one Large or smaller creature within 5 feet. {@actSaveFail} 28 ({@damage 7d6 + 4}) Bludgeoning damage. The target has the {@condition Grappled|XPHB} condition (escape {@dc 14}), and it has the {@condition Restrained|XPHB} condition until the grapple ends. {@actSaveSuccess} Half damage only.

**Poison Spray {@recharge 5}.** {@actSave con} {@dc 14}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 21 ({@damage 6d6}) Poison damage, and the target has the {@condition Poisoned|XPHB} condition until the end of the yuan-ti's next turn. While {@condition Poisoned|XPHB}, the target has the {@condition Blinded|XPHB} condition. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_monstrosity