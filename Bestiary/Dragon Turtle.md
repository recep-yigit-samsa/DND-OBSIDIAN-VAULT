# Dragon Turtle

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dragon Turtle | Dragon | 17 | 356 (23d20 + 115) | 20 | walk: 20 ft., swim: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d10 + 7 + 2d6 | - | - |
| Tail | 2d10 + 7 | - | - |
| Steam Breath {@recharge 5} | 16d6 | 19 | Half Damage ✅ |


**Multiattack.** The dragon makes three Bite attacks. It can replace one attack with a Tail attack.

**Bite.** {@atkr m} {@hit 13}, reach 15 ft. {@h}23 ({@damage 3d10 + 7}) Piercing damage plus 7 ({@damage 2d6}) Fire damage. Being underwater doesn't grant {@variantrule Resistance|XPHB} to this Fire damage.

**Tail.** {@atkr m} {@hit 13}, reach 15 ft. {@h}18 ({@damage 2d10 + 7}) Bludgeoning damage. If the target is a Huge or smaller creature, it has the {@condition Prone|XPHB} condition.

**Steam Breath {@recharge 5}.** {@actSave con} {@dc 19}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 56 ({@damage 16d6}) Fire damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} Being underwater doesn't grant {@variantrule Resistance|XPHB} to this Fire damage.

^Tags: #monster #type_dragon