# Werewolf

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Werewolf | Unknown | 3 | 71 (11d8 + 22) | 15 | walk: 30 ft., alternate: {'walk': [{'number': 40, 'condition': '(wolf form only)'}]} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite (Wolf or Hybrid Form Only) | 2d8 + 3 | 12 | - |
| Scratch | 2d6 + 3 | - | - |
| Longbow (Humanoid or Hybrid Form Only) | 2d8 + 2 | - | - |


**Multiattack.** The werewolf makes two attacks, using Scratch or Longbow in any combination. It can replace one attack with a Bite attack.

**Bite (Wolf or Hybrid Form Only).** {@atkr m} {@hit 5}, reach 5 ft. {@h}12 ({@damage 2d8 + 3}) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. {@actSave con} {@dc 12}. {@actSaveFail} The target is cursed. If the cursed target drops to 0 {@variantrule Hit Points|XPHB}, it instead becomes a Werewolf under the DM's control and has 10 {@variantrule Hit Points|XPHB}. {@actSaveSuccess} The target is immune to this werewolf's curse for 24 hours.

**Scratch.** {@atkr m} {@hit 5}, reach 5 ft. {@h}10 ({@damage 2d6 + 3}) Slashing damage.

**Longbow (Humanoid or Hybrid Form Only).** {@atkr r} {@hit 4}, range 150/600 ft. {@h}11 ({@damage 2d8 + 2}) Piercing damage.

^Tags: #monster #type_unknown