# Guardian Naga

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Guardian Naga | Celestial | 10 | 136 (16d10 + 48) | 18 | walk: 40 ft., climb: 40 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d12 + 4 + 4d10 | - | - |
| Poisonous Spittle | 7d8 | 16 | Half Damage ✅ |


**Multiattack.** The naga makes two Bite attacks. It can replace any attack with a use of Poisonous Spittle.

**Bite.** {@atkr m} {@hit 8}, reach 10 ft. {@h}17 ({@damage 2d12 + 4}) Piercing damage plus 22 ({@damage 4d10}) Poison damage.

**Poisonous Spittle.** {@actSave con} {@dc 16}, one creature the naga can see within 60 feet. {@actSaveFail} 31 ({@damage 7d8}) Poison damage, and the target has the {@condition Blinded|XPHB} condition until the start of the naga's next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_celestial