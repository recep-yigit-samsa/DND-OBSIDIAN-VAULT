# Kraken

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Kraken | Unknown | {'cr': '23', 'xpLair': 62000} | 481 (26d20 + 208) | 18 | walk: 30 ft., swim: 120 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 4d6 + 10 | 20 | - |
| Fling | 4d8 | 25 | Half Damage ✅ |
| Lightning Strike | 6d10 | 23 | Half Damage ✅ |
| Swallow | 3d8 + 10 + 7d6 | 25 | - |


**Multiattack.** The kraken makes two Tentacle attacks and uses Fling, Lightning Strike, or Swallow.

**Tentacle.** {@atkr m} {@hit 17}, reach 30 ft. {@h}24 ({@damage 4d6 + 10}) Bludgeoning damage. The target has the {@condition Grappled|XPHB} condition (escape {@dc 20}) from one of ten tentacles, and it has the {@condition Restrained|XPHB} condition until the grapple ends.

**Fling.** The kraken throws a Large or smaller creature {@condition Grappled|XPHB} by it to a space it can see within 60 feet of itself that isn't in the air. {@actSave dex} {@dc 25}, the creature thrown and each creature in the destination space. {@actSaveFail} 18 ({@damage 4d8}) Bludgeoning damage, and the target has the {@condition Prone|XPHB} condition. {@actSaveSuccess} Half damage only.

**Lightning Strike.** {@actSave dex} {@dc 23}, one creature the kraken can see within 120 feet. {@actSaveFail} 33 ({@damage 6d10}) Lightning damage. {@actSaveSuccess} Half damage.

**Swallow.** {@actSave dex} {@dc 25}, one creature {@condition Grappled|XPHB} by the kraken (it can have up to four creatures swallowed at a time). {@actSaveFail} 23 ({@damage 3d8 + 10}) Piercing damage. If the target is Large or smaller, it is swallowed and no longer {@condition Grappled|XPHB}. A swallowed creature has the {@condition Restrained|XPHB} condition, has {@variantrule Cover|XPHB|Total Cover} against attacks and other effects outside the kraken, and takes 24 ({@damage 7d6}) Acid damage at the start of each of its turns. If the kraken takes 50 damage or more on a single turn from a creature inside it, the kraken must succeed on a {@dc 25} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the kraken with the {@condition Prone|XPHB} condition. If the kraken dies, any swallowed creature no longer has the {@condition Restrained|XPHB} condition and can escape from the corpse using 15 feet of movement, exiting {@condition Prone|XPHB}.

^Tags: #monster #type_unknown