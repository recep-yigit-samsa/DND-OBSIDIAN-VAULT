# Death Knight Aspirant

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Death Knight Aspirant | Undead | 11 | 178 (21d8 + 84) | 20 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Dread Blade | 2d8 + 5 + 3d6 | - | - |
| Hellfire Orb {@recharge 5} | 6d6 + 6d6 | 15 | Half Damage ✅ |


**Multiattack.** The aspirant makes three Dread Blade attacks.

**Dread Blade.** {@atkr m} {@hit 9}, reach 5 ft. {@h}14 ({@damage 2d8 + 5}) Slashing damage plus 10 ({@damage 3d6}) Necrotic damage.

**Hellfire Orb {@recharge 5}.** {@actSave dex} {@dc 15}, each creature in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point the aspirant can see within 120 feet of itself. {@actSaveFail} 21 ({@damage 6d6}) Fire damage plus 21 ({@damage 6d6}) Necrotic damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_undead