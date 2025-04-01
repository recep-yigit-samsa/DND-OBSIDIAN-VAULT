# Juvenile Shadow Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Juvenile Shadow Dragon | Dragon | 4 | 45 (6d8 + 18) | 15 | walk: 30 ft., climb: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 1d8 + 3 + 1d6 | - | - |
| Shadow Breath {@recharge 5} | 5d6 | 13 | Half Damage ✅ |


**Multiattack.** The dragon makes two Rend attacks.

**Rend.** {@atkr m} {@hit 5}, reach 10 ft. {@h}7 ({@damage 1d8 + 3}) Slashing damage plus 3 ({@damage 1d6}) Necrotic damage.

**Shadow Breath {@recharge 5}.** {@actSave dex} {@dc 13}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 17 ({@damage 5d6}) Necrotic damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} A Humanoid reduced to 0 {@variantrule Hit Points|XPHB} by this damage dies, and a {@creature Shadow|XMM} rises from its corpse. The shadow is under the dragon's control and shares the dragon's {@variantrule Initiative|XPHB} count but acts immediately after the dragon.

^Tags: #monster #type_dragon