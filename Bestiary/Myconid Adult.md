# Myconid Adult

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Myconid Adult | Plant | 1/2 | 16 (3d8 + 3) | 12 | walk: 20 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Slam | 1d8 + 1d6 | - | - |
| Pacifying Spores (1/Day) | - | 11 | - |
| Rapport Spores | - | - | - |


**Slam.** {@atkr m} {@hit 2}, reach 5 ft. {@h}4 ({@damage 1d8}) Bludgeoning damage plus 3 ({@damage 1d6}) Poison damage.

**Pacifying Spores (1/Day).** {@actSave con} {@dc 11}, one creature the myconid can see within 10 feet. {@actSaveFail} The target has the {@condition Stunned|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

**Rapport Spores.** The myconid expels spores in a 30-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from itself. Creatures in that area with an Intelligence score of 2 or higher that aren't Constructs, Elementals, or Undead gain telepathy with a range of 30 feet for 1 hour.

^Tags: #monster #type_plant