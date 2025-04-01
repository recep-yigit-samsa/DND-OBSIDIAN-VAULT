# Salamander Inferno Master

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Salamander Inferno Master | Elemental | 15 | 256 (27d10 + 108) | 18 | walk: 40 ft., climb: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Flame Trident | 2d8 + 7 + 4d6 | - | - |
| Inferno Blast {@recharge 5} | 10d6 + 1d10 | 18 | Half Damage ✅ |


**Multiattack.** The salamander makes two Flame Trident attacks.

**Flame Trident.** {@atkr m,r} {@hit 12}, reach 5 ft. or range 30/90 ft. {@h}16 ({@damage 2d8 + 7}) Piercing damage plus 14 ({@damage 4d6}) Fire damage. {@hom}The trident magically returns to the salamander's hand immediately after a ranged attack.

**Inferno Blast {@recharge 5}.** {@actSave dex} {@dc 18}, each creature in a 30-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point the salamander can see within 120 feet. {@actSaveFail} 35 ({@damage 10d6}) Fire damage, and the target starts burning, taking 5 ({@damage 1d10}) Fire damage at the start of each of its turns instead of the normal burning damage. The target gains 1 {@condition Exhaustion|XPHB} level whenever it takes this burning damage. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_elemental