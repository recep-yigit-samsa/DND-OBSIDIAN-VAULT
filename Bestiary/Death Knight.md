# Death Knight

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Death Knight | Undead | 17 | 199 (21d8 + 105) | 20 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Dread Blade | 2d6 + 5 + 3d8 | - | - |
| Hellfire Orb {@recharge 5} | 10d6 + 10d6 | 18 | Half Damage ✅ |


**Multiattack.** The death knight makes three Dread Blade attacks.

**Dread Blade.** {@atkr m} {@hit 11}, reach 5 ft. {@h}12 ({@damage 2d6 + 5}) Slashing damage plus 13 ({@damage 3d8}) Necrotic damage.

**Hellfire Orb {@recharge 5}.** {@actSave dex} {@dc 18}, each creature in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point the death knight can see within 120 feet. {@actSaveFail} 35 ({@damage 10d6}) Fire damage plus 35 ({@damage 10d6}) Necrotic damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_undead