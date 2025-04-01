# Planetar

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Planetar | Unknown | 16 | 262 (21d10 + 147) | 19 | walk: 40 ft., fly: {'number': 120, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Radiant Sword | 2d6 + 7 + 4d8 | - | - |
| Holy Burst | 7d6 | 20 | Half Damage ✅ |


**Multiattack.** The planetar makes three Radiant Sword attacks or uses Holy Burst twice.

**Radiant Sword.** {@atkr m} {@hit 12}, reach 10 ft. {@h}14 ({@damage 2d6 + 7}) Slashing damage plus 18 ({@damage 4d8}) Radiant damage.

**Holy Burst.** {@actSave dex} {@dc 20}, each enemy in a 20-foot-radius {@variantrule Sphere [Area of Effect]|XPHB|Sphere} centered on a point the planetar can see within 120 feet. {@actSaveFail} 24 ({@damage 7d6}) Radiant damage. {@actSaveSuccess} Half damage.

^Tags: #monster #type_unknown