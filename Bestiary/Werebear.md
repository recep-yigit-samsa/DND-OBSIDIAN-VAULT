# Werebear

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Werebear | Unknown | 5 | 135 (18d8 + 54) | 15 | walk: 30 ft., alternate: {'walk': [{'number': 40, 'condition': '(bear form only)'}]} ft., climb: {'number': 30, 'condition': '(bear form only)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite (Bear or Hybrid Form Only) | 2d12 + 4 | 14 | - |
| Handaxe (Humanoid or Hybrid Form Only) | 3d6 + 4 | - | - |
| Rend (Bear or Hybrid Form Only) | 2d8 + 4 | - | - |


**Multiattack.** The werebear makes two attacks, using Handaxe or Rend in any combination. It can replace one attack with a Bite attack.

**Bite (Bear or Hybrid Form Only).** {@atkr m} {@hit 7}, reach 5 ft. {@h}17 ({@damage 2d12 + 4}) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. {@actSave con} {@dc 14}. {@actSaveFail} The target is cursed. If the cursed target drops to 0 {@variantrule Hit Points|XPHB}, it instead becomes a Werebear under the DM's control and has 10 {@variantrule Hit Points|XPHB}. {@actSaveSuccess} The target is immune to this werebear's curse for 24 hours.

**Handaxe (Humanoid or Hybrid Form Only).** {@atkr m,r} {@hit 7}, reach 5 ft or range 20/60 ft. {@h}14 ({@damage 3d6 + 4}) Slashing damage.

**Rend (Bear or Hybrid Form Only).** {@atkr m} {@hit 7}, reach 5 ft. {@h}13 ({@damage 2d8 + 4}) Slashing damage.

^Tags: #monster #type_unknown