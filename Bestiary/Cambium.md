# Cambium

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cambium | Fiend | 14 | 264 (23d10 + 138) | 19 | walk: 40 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Needle Fingers | 3d10 + 5 | - | - |
| Poison Ray | 4d8 + 4 | 17 | - |


**Multiattack.** The cambium makes four Needle Fingers or Poison Ray attacks. It can replace two attacks with a use of Spellcasting.

**Needle Fingers.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}21 ({@damage 3d10 + 5}) piercing damage.

**Poison Ray.** {@atk rs} {@hit 9} to hit, range 60 ft., one target. {@h}22 ({@damage 4d8 + 4}) poison damage, and the target must succeed on a {@dc 17} Constitution saving throw or become {@condition poisoned} until the end of its next turn.

^Tags: #monster #type_fiend