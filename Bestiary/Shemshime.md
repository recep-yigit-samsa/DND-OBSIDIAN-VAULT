# Shemshime

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shemshime | Undead | 4 | 31 (7d8) | 13 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Maddening Touch | 4d6 + 3 | - | - |
| Whispers of Violence | 1d8 + 3 | 13 | - |
| Howling Babble {@recharge} | 4d8 + 3 | 13 | - |


**Maddening Touch.** {@atk ms} {@hit 5} to hit, reach 5 ft., one target. {@h}17 ({@damage 4d6 + 3}) psychic damage.

**Whispers of Violence.** Shemshime chooses up to two creatures it can see within 60 feet of it. Each target must succeed on a {@dc 13} Wisdom saving throw, or that target takes 7 ({@damage 1d8 + 3}) psychic damage and must use its reaction to make a melee weapon attack against one creature it can reach (Shemshime's choice) that Shemshime can see.

**Howling Babble {@recharge}.** Shemshime targets one creature it can see within 30 feet of it. The creature must make a {@dc 13} Wisdom saving throw. On a failed save, it takes 21 ({@damage 4d8 + 3}) psychic damage and is {@condition stunned} until the end of its next turn. On a successful save, it takes half as much damage and isn't {@condition stunned}.

^Tags: #monster #type_undead