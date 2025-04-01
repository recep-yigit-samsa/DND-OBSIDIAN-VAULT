# Umbral Vampire

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Umbral Vampire | Undead | 7 | 84 (13d8 + 26) | 14 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Shadow Touch | 3d8 + 4 | - | - |
| Umbral Grasp | 2d8 | 15 | - |


**Multiattack.** The umbral vampire can use its Umbral Grasp. It then makes two Shadow Touch attacks.

**Shadow Touch.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}17 ({@damage 3d8 + 4}) necrotic damage, and the target's Strength score is reduced by {@dice 1d4}. The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest. A non-evil Humanoid slain by this attack rises 24 hours later as a shadow under the vampire's control, unless the Humanoid is restored to life. The vampire can have no more than five shadows under its control at one time.

**Umbral Grasp.** The umbral vampire sends a giant hand of shadow to grab one creature it can see that is in dim light or darkness within 30 feet of it. The target must succeed on a {@dc 15} Dexterity saving throw or be {@condition restrained} by wisps of magical shadow for 1 minute. While {@condition restrained}, the target takes 9 ({@damage 2d8}) necrotic damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The umbral vampire can have no more than two creatures {@condition restrained} by its Umbral Grasp at a time.

^Tags: #monster #type_undead