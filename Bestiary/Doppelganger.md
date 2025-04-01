# Doppelganger

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Doppelganger | Monstrosity | 3 | 52 (8d8 + 16) | 14 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d6 + 4 | - | - |
| Unsettling Visage {@recharge} | - | 12 | - |


**Multiattack.** The doppelganger makes two Slam attacks and uses Unsettling Visage if available.

**Slam.** {@atkr m} {@hit 6} (with {@variantrule Advantage|XPHB} during the first round of each combat), reach 5 ft. {@h}11 ({@damage 2d6 + 4}) Bludgeoning damage.

**Unsettling Visage {@recharge}.** {@actSave wis} {@dc 12}, each creature in a 15-foot {@variantrule Emanation [Area of Effect]|XPHB|Emanation} originating from the doppelganger that can see the doppelganger. {@actSaveFail} The target has the {@condition Frightened|XPHB} condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

^Tags: #monster #type_monstrosity