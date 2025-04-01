# Shadow Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shadow Dragon | Dragon | {'cr': '13', 'xpLair': 11500} | 189 (18d12 + 72) | 16 | walk: 40 ft., climb: 40 ft., fly: 80 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d6 + 5 + 1d6 | - | - |
| Shadow Breath {@recharge 5} | 10d6 | 17 | Half Damage ✅ |


**Multiattack.** The dragon makes three Rend attacks.

**Rend.** {@atkr m} {@hit 10}, reach 10 ft. {@h}12 ({@damage 2d6 + 5}) Slashing damage plus 3 ({@damage 1d6}) Necrotic damage.

**Shadow Breath {@recharge 5}.** {@actSave dex} {@dc 17}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 35 ({@damage 10d6}) Necrotic damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} A Humanoid reduced to 0 {@variantrule Hit Points|XPHB} by this damage dies, and a {@creature Shadow|XMM} rises from the corpse. The shadow is under the dragon's control and shares the dragon's {@variantrule Initiative|XPHB} count but acts immediately after the dragon.

^Tags: #monster #type_dragon