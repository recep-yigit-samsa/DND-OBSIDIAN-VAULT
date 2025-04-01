# Myconid Sovereign

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Myconid Sovereign | Plant | 2 | 45 (6d10 + 12) | 13 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d4 + 1 + 2d4 | - | - |
| Animating Spores (3/Day) | - | - | - |
| Pacifying Spores | - | 12 | - |
| Rapport Spores | - | - | - |


**Multiattack.** The myconid makes one Slam attack and uses Pacifying Spores.

**Slam.** {@atkr m} {@hit 3}, reach 5 ft. {@h}6 ({@damage 2d4 + 1}) Bludgeoning damage plus 5 ({@damage 2d4}) Poison damage.

**Animating Spores (3/Day).** The myconid releases spores at a Medium or Small corpse within 5 feet of it that wasn't a Construct or an Undead. In 24 hours, the corpse rises as a {@creature Myconid Spore Servant|XMM}. The corpse stays animate for {@dice 1d4 + 1} weeks or until destroyed, and it can't be animated again in this way.

**Pacifying Spores.** {@actSave con} {@dc 12}, one creature the myconid can see within 10 feet. {@actSaveFail} The target has the {@condition Stunned|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

**Rapport Spores.** The myconid expels spores in a 30-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from itself. Creatures in that area with an Intelligence score of 2 or higher that aren't Constructs, Elementals, or Undead gain telepathy with a range of 30 feet for 1 hour.

^Tags: #monster #type_plant