# Breath Drinker

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Breath Drinker | Aberration | 14 | 157 (21d8 + 63) | 18 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Enervating Claw | 2d6 + 5 | 18 | - |
| Drink Breath | 8d8 | 18 | - |
| Invisibility | - | - | - |


**Multiattack.** The breath drinker makes two Enervating Claw attacks. It can also use Drink Breath.

**Enervating Claw.** {@atk mw} {@hit 10} to hit, reach 5 ft., one creature. {@h}12 ({@damage 2d6 + 5}) necrotic damage, and if the target is Large or smaller, it has the {@condition grappled} condition (escape {@dc 18}). The target must succeed on a {@dc 18} Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

**Drink Breath.** The breath drinker targets a creature that has the {@condition incapacitated} condition or that the breath drinker is grappling and that isn't a Construct or an Undead. The target must make a {@dc 18} Charisma saving throw. On a failed save, the target takes 36 ({@damage 8d8}) necrotic damage, and its Charisma score is reduced by {@dice 1d6}. This reduction lasts until the target finishes a short or long rest. If this reduces the target's Charisma to 0, the target dies. Until the breath drinker dies, the dead target can't be returned to life by any means short of divine intervention. On a successful save, the target takes half as much necrotic damage only. On a successful or failed save, the breath drinker regains a number of hit points equal to the necrotic damage dealt.

**Invisibility.** The breath drinker has the {@condition invisible} condition. This invisibility ends immediately after the breath drinker hits or misses with an attack roll or uses Drink Breath.

^Tags: #monster #type_aberration