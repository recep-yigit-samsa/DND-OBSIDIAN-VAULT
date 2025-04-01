# Marut

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Marut | Unknown | 25 | 432 (32d10 + 256) | 22 | walk: 40 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Unerring Slam | - | - | - |
| Blazing Edict {@recharge 5} | - | 20 | - |
| Justify | - | 20 | - |


**Multiattack.** The marut makes two slam attacks.

**Unerring Slam.** {@atk mw} automatic hit, reach 5 ft., one target. {@h}60 force damage, and the target is pushed up to 5 feet away from the marut if it is Huge or smaller.

**Blazing Edict {@recharge 5}.** Arcane energy emanates from the marut's chest in a 60-foot cube. Every creature in that area takes 45 radiant damage. Each creature that takes any of this damage must succeed on a {@dc 20} Wisdom saving throw or be {@condition stunned} until the end of the marut's next turn.

**Justify.** The marut targets up to two creatures it can see within 60 feet of it. Each target must succeed on a {@dc 20} Charisma saving throw or be teleported to a teleportation circle in the Hall of Concordance in Sigil. A target fails automatically if it is {@condition incapacitated}. If either target is teleported in this way, the marut teleports with it to the circle. After teleporting in this way, the marut can't use this action again until it finishes a short or long rest.

^Tags: #monster #type_unknown