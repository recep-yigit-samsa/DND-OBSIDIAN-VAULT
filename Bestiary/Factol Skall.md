# Factol Skall

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Factol Skall | Unknown | 17 | 210 (28d8 + 84) | 17 | walk: 30 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Withering Touch | 6d8 + 5 + 7d8 | - | - |
| Death Knell | 4d6 | 19 | - |
| Fog of Death (1/Day) | 8d6 + 8d6 | 19 | - |


**Multiattack.** Skall makes one Withering Touch attack or uses Spellcasting. He also uses Death Knell twice.

**Withering Touch.** {@atk ms} {@hit 11} to hit, reach 5 ft., one target. {@h}32 ({@damage 6d8 + 5}) cold damage plus 31 ({@damage 7d8}) necrotic damage, and if the target is a creature, it can't regain hit points until the start of Skall's next turn.

**Death Knell.** Skall points his finger at a creature he can see within 120 feet of himself, filling the target's mind with visions of death and the plangent toll of an iron bell. The target must succeed on a {@dc 19} Wisdom saving throw or take 14 ({@damage 4d6}) psychic damage and have the {@condition frightened} condition until the start of Skall's next turn.

**Fog of Death (1/Day).** Skall exudes a killing fog in a 30-foot-radius sphere centered on himself. The sphere spreads around corners, and its area is heavily obscured. The fog lasts until the start of Skall's next turn, and it can't be dispersed by wind. It does not move with him. Each creature that enters the fog for the first time on a turn or starts its turn there must make a {@dc 19} Constitution saving throw, taking 28 ({@damage 8d6}) necrotic damage and 28 ({@damage 8d6}) poison damage on a failed save, or half as much damage on a successful one. A Medium or smaller Humanoid killed by this damage becomes a zombie under Skall's control. The zombie acts on Skall's initiative but immediately after his turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.

^Tags: #monster #type_unknown