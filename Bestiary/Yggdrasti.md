# Yggdrasti

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Yggdrasti | Plant | 7 | 112 (9d20 + 18) | 15 | walk: 30 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Root | 2d6 + 5 | 15 | - |
| Lightning Discharge (3/Day) | 7d8 | 13 | - |


**Multiattack.** The yggdrasti makes two Root attacks and uses Lightning Discharge (if available).

**Root.** {@atk mw} {@hit 8} to hit, reach 20 ft., one target. {@h}12 ({@damage 2d6 + 5}) bludgeoning damage, and if the target is a creature, it is {@condition grappled} (escape {@dc 15}). The yggdrasti has four roots, each of which can grapple one target.

**Lightning Discharge (3/Day).** The yggdrasti shoots lightning at one creature within 120 feet of itself. The target must make a {@dc 13} Dexterity saving throw, taking 31 ({@damage 7d8}) lightning damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_plant