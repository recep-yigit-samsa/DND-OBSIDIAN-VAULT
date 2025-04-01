# Gulthias Blight

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gulthias Blight | Plant | 16 | 264 (16d20 + 96) | 20 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 4d8 + 7 | - | - |
| Thorn Volley | 3d8 + 7 | - | - |
| Life-Draining Root | 2d6 + 7 + 4d6 | 20 | - |


**Multiattack.** The blight makes two attacks, using Slam or Thorn Volley in any combination. It also uses Life-Draining Root.

**Slam.** {@atkr m} {@hit 12}, reach 10 ft. {@h}25 ({@damage 4d8 + 7}) Bludgeoning damage.

**Thorn Volley.** {@atkr r} {@hit 12}, range 60/180 ft. {@h}20 ({@damage 3d8 + 7}) Piercing damage.

**Life-Draining Root.** {@actSave con} {@dc 20}, one Huge or smaller creature the blight can see within 30 feet. {@actSaveFail} 14 ({@damage 2d6 + 7}) Necrotic damage, and the target has the {@condition Grappled|XPHB} condition (escape {@dc 17}) from one of six roots. Until the grapple ends, the target has the {@condition Restrained|XPHB} condition and takes 14 ({@damage 4d6}) Necrotic damage at the start of each of its turns. The target's {@variantrule Hit Points|XPHB|Hit Point} maximum decreases by an amount equal to the Necrotic damage taken, and the blight regains {@variantrule Hit Points|XPHB} equal to that amount.

^Tags: #monster #type_plant