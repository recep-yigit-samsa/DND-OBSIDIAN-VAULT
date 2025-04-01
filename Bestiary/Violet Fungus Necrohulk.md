# Violet Fungus Necrohulk

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Violet Fungus Necrohulk | Plant | 7 | 123 (13d10 + 52) | 17 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rotting Slam | 1d10 + 4 + 2d6 | - | - |
| Spore Bomb {@recharge 5} | 8d6 | 15 | Half Damage ✅ |


**Multiattack.** The necrohulk makes two Rotting Slam attacks.

**Rotting Slam.** {@atkr m} {@hit 7}, reach 10 ft. {@h}9 ({@damage 1d10 + 4}) Bludgeoning damage plus 7 ({@damage 2d6}) Necrotic damage.

**Spore Bomb {@recharge 5}.** {@actSave con} {@dc 15}, each creature in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point the necrohulk can see within 60 feet. {@actSaveFail} 28 ({@damage 8d6}) Necrotic damage, and the target has the {@condition Poisoned|XPHB} condition until the start of the necrohulk's next turn. While {@condition Poisoned|XPHB}, the target can't regain {@variantrule Hit Points|XPHB}. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_plant