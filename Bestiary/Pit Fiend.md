# Pit Fiend

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Pit Fiend | Unknown | 20 | 337 (27d10 + 189) | 21 | walk: 30 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d6 + 8 + 6d6 | 21 | - |
| Devilish Claw | 4d8 + 8 | - | - |
| Fiery Mace | 4d6 + 8 + 6d6 | - | - |


**Multiattack.** The pit fiend makes one Bite attack, two Devilish Claw attacks, and one Fiery Mace attack.

**Bite.** {@atkr m} {@hit 14}, reach 10 ft. {@h}18 ({@damage 3d6 + 8}) Piercing damage. If the target is a creature, it must make the following saving throw. {@actSave con} {@dc 21}. {@actSaveFail} The target has the {@condition Poisoned|XPHB} condition. While {@condition Poisoned|XPHB}, the target can't regain {@variantrule Hit Points|XPHB} and takes 21 ({@damage 6d6}) Poison damage at the start of each of its turns, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

**Devilish Claw.** {@atkr m} {@hit 14}, reach 10 ft. {@h}26 ({@damage 4d8 + 8}) Necrotic damage.

**Fiery Mace.** {@atkr m} {@hit 14}, reach 10 ft. {@h}22 ({@damage 4d6 + 8}) Force damage plus 21 ({@damage 6d6}) Fire damage.

^Tags: #monster #type_unknown