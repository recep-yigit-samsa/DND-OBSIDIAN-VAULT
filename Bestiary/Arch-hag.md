# Arch-hag

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Arch-hag | Fey | {'cr': '21', 'xpLair': 41000} | 333 (29d10 + 174) | 20 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Spectral Claw | 3d6 + 7 | - | - |
| Crackling Wave | 5d12 | 22 | Half Damage ✅ |


**Multiattack.** The hag makes two Spectral Claw attacks and uses Crackling Wave.

**Spectral Claw.** {@atkr m,r} {@hit 14}, reach 10 ft. or range 60 ft. {@h}17 ({@damage 3d6 + 7}) Force damage. If the target is a Large or smaller creature, it has the {@condition Prone|XPHB} condition.

**Crackling Wave.** {@actSave dex} {@dc 22}, each creature in a 60-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 32 ({@damage 5d12}) Lightning damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} The target is cursed until the end of the hag's next turn. The target can't take Reactions until the curse ends.

^Tags: #monster #type_fey