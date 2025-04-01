# Wererat

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Wererat | Unknown | 2 | 60 (11d8 + 11) | 13 | walk: 30 ft., climb: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite (Rat or Hybrid Form Only) | 2d4 + 3 | 11 | - |
| Scratch | 1d6 + 3 | - | - |
| Hand Crossbow (Humanoid or Hybrid Form Only) | 1d6 + 3 | - | - |


**Multiattack.** The wererat makes two attacks, using Scratch or Hand Crossbow in any combination. It can replace one attack with a Bite attack.

**Bite (Rat or Hybrid Form Only).** {@atkr m} {@hit 5}, reach 5 ft. {@h}8 ({@damage 2d4 + 3}) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. {@actSave con} {@dc 11}. {@actSaveFail} The target is cursed. If the cursed target drops to 0 {@variantrule Hit Points|XPHB}, it instead becomes a Wererat under the DM's control and has 10 {@variantrule Hit Points|XPHB}. {@actSaveSuccess} The target is immune to this wererat's curse for 24 hours.

**Scratch.** {@atkr m} {@hit 5}, reach 5 ft. {@h}6 ({@damage 1d6 + 3}) Slashing damage.

**Hand Crossbow (Humanoid or Hybrid Form Only).** {@atkr r} {@hit 5}, range 30/120 ft. {@h}6 ({@damage 1d6 + 3}) Piercing damage.

^Tags: #monster #type_unknown