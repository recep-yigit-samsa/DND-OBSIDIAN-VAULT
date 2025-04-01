# Wereboar

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Wereboar | Unknown | 4 | 97 (15d8 + 30) | 15 | walk: 30 ft., alternate: {'walk': [{'number': 40, 'condition': '(boar form only)'}]} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Gore (Boar or Hybrid Form Only) | 2d8 + 3 | 12 | - |
| Javelin (Humanoid or Hybrid Form Only) | 3d6 + 3 | - | - |
| Tusk (Boar or Hybrid Form Only) | 2d6 + 3 + 2d6 | - | - |


**Multiattack.** The wereboar makes two attacks, using Javelin or Tusk in any combination. It can replace one attack with a Gore attack.

**Gore (Boar or Hybrid Form Only).** {@atkr m} {@hit 5}, reach 5 ft. {@h}12 ({@damage 2d8 + 3}) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. {@actSave con} {@dc 12}. {@actSaveFail} The target is cursed. If the cursed target drops to 0 {@variantrule Hit Points|XPHB}, it instead becomes a Wereboar under the DM's control and has 10 {@variantrule Hit Points|XPHB}. {@actSaveSuccess} The target is immune to this wereboar's curse for 24 hours.

**Javelin (Humanoid or Hybrid Form Only).** {@atkr m,r} {@hit 5}, reach 5 ft. or range 30/120 ft. {@h}13 ({@damage 3d6 + 3}) Piercing damage.

**Tusk (Boar or Hybrid Form Only).** {@atkr m} {@hit 5}, reach 5 ft. {@h}10 ({@damage 2d6 + 3}) Piercing damage. If the target is a Medium or smaller creature and the wereboar moved 20+ feet straight toward it immediately before the hit, the target takes an extra 7 ({@damage 2d6}) Piercing damage and has the {@condition Prone|XPHB} condition.

^Tags: #monster #type_unknown