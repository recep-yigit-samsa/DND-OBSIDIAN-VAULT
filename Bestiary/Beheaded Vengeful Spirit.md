# Beheaded Vengeful Spirit

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Beheaded Vengeful Spirit | Undead | 4 | 54 (12d8) | 15 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Essence of Rage | 4d8 + 4 | 14 | - |
| Decapitation (1/Day) | 8d6 | 14 | - |


**Essence of Rage.** {@atk ms,rs} {@hit 6} to hit, reach 5 ft. or range 30 ft., one creature. {@h}22 ({@damage 4d8 + 4}) psychic damage, and the target must succeed on a {@dc 14} Charisma saving throw or be enraged until the end of its next turn. While enraged, the target has advantage on melee attack rolls and must move to and attack the nearest creature other than the spirit. In addition, attack rolls against the enraged target have advantage.

**Decapitation (1/Day).** The vengeful spirit makes a quick, cutting gesture at one creature it can see within 30 feet of it that has a head and that is below half its hp maximum. The target must make a {@dc 14} Constitution saving throw, taking 28 ({@damage 8d6}) slashing damage on a failed save, or half as much damage on a successful one. A target that fails the saving throw also has one of its heads cut off. The creature dies if it can't survive without the lost head.

^Tags: #monster #type_undead