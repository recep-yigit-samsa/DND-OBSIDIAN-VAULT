# Iron Golem

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Iron Golem | Construct | 16 | 252 (24d10 + 120) | 20 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bladed Arm | 3d8 + 7 + 3d6 | - | - |
| Fiery Bolt | 8d8 | - | - |
| Poison Breath {@recharge} | 10d10 | 18 | Half Damage ✅ |


**Multiattack.** The golem makes two attacks, using Bladed Arm or Fiery Bolt in any combination.

**Bladed Arm.** {@atkr m} {@hit 12}, reach 10 ft. {@h}20 ({@damage 3d8 + 7}) Slashing damage plus 10 ({@damage 3d6}) Fire damage.

**Fiery Bolt.** {@atkr r} {@hit 10}, range 120 ft. {@h}36 ({@damage 8d8}) Fire damage.

**Poison Breath {@recharge}.** {@actSave con} {@dc 18}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 55 ({@damage 10d10}) Poison damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_construct