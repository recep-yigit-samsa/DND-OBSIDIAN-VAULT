# Modron Pentadrone

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Modron Pentadrone | Construct | 2 | 32 (5d10 + 5) | 16 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 1d6 + 2 | - | - |
| Electrical Discharge | 1d6 + 2 | - | - |
| Paralysis Gas {@recharge 5} | - | 11 | - |


**Multiattack.** The modron makes five Slam attacks or five Electrical Discharge attacks.

**Slam.** {@atkr m} {@hit 4}, reach 5 ft. {@h}5 ({@damage 1d6 + 2}) Force damage.

**Electrical Discharge.** {@atkr r} {@hit 4}, range 120 ft. {@h}5 ({@damage 1d6 + 2}) Lightning damage.

**Paralysis Gas {@recharge 5}.** Constitution Saving Throws: {@dc 11}, each creature in a 30-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} The target has the {@condition Paralyzed|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_construct