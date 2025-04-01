# Allip

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Allip | Undead | 5 | 40 (9d8) | 13 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Maddening Touch | 4d6 + 3 | - | - |
| Whispers of Madness | 1d8 + 3 | 14 | - |
| Howling Babble {@recharge} | 2d8 + 3 | 14 | - |


**Maddening Touch.** {@atk ms} {@hit 6} to hit, reach 5 ft., one target. {@h}17 ({@damage 4d6 + 3}) psychic damage.

**Whispers of Madness.** The allip chooses up to three creatures it can see within 60 feet of it. Each target must succeed on a {@dc 14} Wisdom saving throw, or it takes 7 ({@damage 1d8 + 3}) psychic damage and must use its reaction to make a melee weapon attack against one creature of the allip's choice that the allip can see. Constructs and undead are immune to this effect.

**Howling Babble {@recharge}.** Each creature within 30 feet of the allip that can hear it must make a {@dc 14} Wisdom saving throw. On a failed save, a target takes 12 ({@damage 2d8 + 3}) psychic damage, and it is {@condition stunned} until the end of its next turn. On a successful save, it takes half as much damage and isn't {@condition stunned}. Constructs and undead are immune to this effect.

^Tags: #monster #type_undead