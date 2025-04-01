# Glabrezu

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Glabrezu | Unknown | 9 | 189 (18d10 + 90) | 17 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Pincer | 2d10 + 5 | 15 | - |
| Pummel | 3d6 + 5 | 17 | Half Damage ✅ |


**Multiattack.** The glabrezu makes two Pincer attacks and uses Pummel or Spellcasting.

**Pincer.** {@atkr m} {@hit 9}, reach 10 ft. {@h}16 ({@damage 2d10 + 5}) Slashing damage. If the target is a Medium or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 15}) from one of two pincers.

**Pummel.** {@actSave dex} {@dc 17}, one creature {@condition Grappled|XPHB} by the glabrezu. {@actSaveFail} 15 ({@damage 3d6 + 5}) Bludgeoning damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown