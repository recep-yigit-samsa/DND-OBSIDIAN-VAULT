# Vampire Umbral Lord

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vampire Umbral Lord | Undead | {'cr': '15', 'xpLair': 15000} | 187 (22d8 + 88) | 16 | walk: 40 ft., climb: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Grave Strike | 1d8 + 5 + 3d8 | - | - |
| Sickening Ray | 2d10 + 5 | - | - |


**Multiattack.** The vampire makes two attacks, using Grave Strike or Sickening Ray in any combination.

**Grave Strike.** {@atkr m} {@hit 10}, reach 5 ft. {@h}9 ({@damage 1d8 + 5}) Slashing damage plus 13 ({@damage 3d8}) Necrotic damage.

**Sickening Ray.** {@atkr r} {@hit 10}, range 120 ft. {@h}16 ({@damage 2d10 + 5}) Necrotic damage, and the target has the {@condition Poisoned|XPHB} condition until the start of the vampire's next turn.

^Tags: #monster #type_undead