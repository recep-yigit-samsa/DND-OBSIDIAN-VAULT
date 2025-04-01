# Primeval Owlbear

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Primeval Owlbear | Monstrosity | 7 | 126 (12d12 + 48) | 16 | walk: 40 ft., climb: 40 ft., fly: 5 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Ravage | 2d8 + 6 + 2d8 | - | - |
| Screech {@recharge 5} | 6d8 | 15 | Half Damage ✅ |


**Multiattack.** The owlbear makes two Ravage attacks.

**Ravage.** {@atkr m} {@hit 9}, reach 5 ft. {@h}15 ({@damage 2d8 + 6}) Slashing damage. If the target is a Huge or smaller creature and the owlbear moved 20+ feet straight toward it immediately before the hit, the target takes an extra 9 ({@damage 2d8}) Slashing damage and has the {@condition Prone|XPHB} condition.

**Screech {@recharge 5}.** {@actSave con} {@dc 15}, each creature in a 30-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the owlbear. {@actSaveFail} 27 ({@damage 6d8}) Thunder damage, and the target has the {@condition Incapacitated|XPHB} condition until the end of its next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_monstrosity