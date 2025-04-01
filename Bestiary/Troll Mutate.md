# Troll Mutate

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Troll Mutate | Giant | 7 | 95 (10d10 + 40) | 16 | walk: 30 ft., fly: {'number': 30, 'condition': '(winged form only)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Rend | 2d10 + 4 + 2d8 | - | - |
| Psychic Burst {@recharge 5} | 8d6 | 14 | - |


**Multiattack.** The mutate makes two Rend attacks.

**Rend.** {@atk mw} {@hit 7} to hit, reach 5 ft. (or 15 ft. if the mutate has the Elastic Body mutation), one target. {@h}15 ({@damage 2d10 + 4}) slashing damage plus 9 ({@damage 2d8}) force damage.

**Psychic Burst {@recharge 5}.** The mutate unleashes a wave of psychic energy. Each creature within 30 feet of the mutate must make a {@dc 14} Intelligence saving throw, taking 28 ({@damage 8d6}) psychic damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_giant