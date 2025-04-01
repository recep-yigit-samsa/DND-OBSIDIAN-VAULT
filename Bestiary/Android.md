# Android

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Android | Construct | 5 | 91 (14d8 + 28) | 15 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover; aerialist only)'} ft., swim: {'number': 30, 'condition': '(diver only)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Force Strike | 2d10 + 4 | 15 | - |


**Multiattack.** The android makes two Force Strike attacks.

**Force Strike.** {@atk mw,rw} {@hit 7} to hit, reach 5 ft. or range 40/120 ft., one target. {@h}15 ({@damage 2d10 + 4}) force damage. If the target is a Medium or smaller creature, it must succeed on a {@dc 15} Strength saving throw or have the {@condition prone} condition.

^Tags: #monster #type_construct