# Storm Giant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Storm Giant | Giant | 13 | 230 (20d12 + 100) | 16 | walk: 50 ft., fly: {'number': 25, 'condition': '(hover)'} ft., swim: 50 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Storm Sword | 4d6 + 9 + 3d8 | - | - |
| Thunderbolt | 2d12 + 9 | - | - |
| Lightning Storm {@recharge 5} | 10d10 | 18 | Half Damage ✅ |


**Multiattack.** The giant makes two attacks, using Storm Sword or Thunderbolt in any combination.

**Storm Sword.** {@atkr m} {@hit 14}, reach 10 ft. {@h}23 ({@damage 4d6 + 9}) Slashing damage plus 13 ({@damage 3d8}) Lightning damage.

**Thunderbolt.** {@atkr r} {@hit 14}, range 500 ft. {@h}22 ({@damage 2d12 + 9}) Lightning damage, and the target has the {@condition Blinded|XPHB} and {@condition Deafened|XPHB} conditions until the start of the giant's next turn.

**Lightning Storm {@recharge 5}.** {@actSave dex} {@dc 18}, each creature in a 10-foot-radius, 40-foot-high {@variantrule Cylinder [Area of Effect]|XPHB|Cylinder} originating from a point the giant can see within 500 feet. {@actSaveFail} 55 ({@damage 10d10}) Lightning damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_giant