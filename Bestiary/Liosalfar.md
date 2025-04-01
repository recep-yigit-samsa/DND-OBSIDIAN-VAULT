# Liosalfar

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Liosalfar | Elemental | 10 | 132 (24d10) | 17 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | 16 | - |
| Radiant Touch | 4d10 + 7 | - | - |
| Ray of Light | 6d8 + 4 | 16 | - |
| Mesmerizing Radiance | - | 16 | - |


**Multiattack.** The liosalfar makes two Radiant Touch or Ray of Light attacks. If both Radiant Touch attacks hit one creature, the target must succeed on a {@dc 16} Constitution saving throw or be {@condition stunned} until the end of its next turn.

**Radiant Touch.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}29 ({@damage 4d10 + 7}) radiant damage.

**Ray of Light.** {@atk rs} {@hit 8} to hit, range 60 ft., one target. {@h}31 ({@damage 6d8 + 4}) radiant damage, and the target must succeed on a {@dc 16} Constitution saving throw or be {@condition blinded} until the end of its next turn.

**Mesmerizing Radiance.** The liosalfar causes the light radiating from its body to shift color and pattern in a spellbinding display. Each creature within 60 feet of the liosalfar and that can see it must succeed on a {@dc 16} Wisdom saving throw or be {@condition charmed} until the display ends. The liosalfar must take a bonus action on its subsequent turns to continue the display. It can stop the display at any time, and the display ends if the liosalfar is {@condition incapacitated}. While {@condition charmed} by the liosalfar's display, a creature is also {@condition incapacitated}, and its speed is reduced to 0, as it is transfixed by the display. The effect ends for a {@condition charmed} creature if it takes any damage or if someone uses an action to shake the creature out of its stupor.

^Tags: #monster #type_elemental