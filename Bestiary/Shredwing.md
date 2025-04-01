# Shredwing

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Shredwing | Fiend | 12 | 170 (20d8 + 80) | 21 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Talon | 2d6 + 4 + 2d6 | - | - |
| Burrow {@recharge 5} | 5d12 + 3d12 | - | - |


**Multiattack.** The shredwing makes three Talon attacks.

**Talon.** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage plus 7 ({@damage 2d6}) poison damage.

**Burrow {@recharge 5}.** On a hit, the creature takes an additional 32 ({@damage 5d12}) slashing damage as the wings merge with it. While merged, the creature moves with the shredwing, takes 19 ({@damage 3d12}) necrotic damage at the start of each of its turn, and has the {@condition grappled} condition. The shredwing can unmerge at any time, leaving the creature and dropping it if airborne. The only other way to end the merge is to kill the shredwing. If the merged creature dies while merged, the shredwing permanently takes over its body. It gains the merged creature's hit dice, natural armor, possessions, and languages. If any of the merged creature's statistics are higher than the shredwing, it inherits those statistics as well. A creature permanently merged by the shredwing can only be resurrected through a {@spell Wish} spell or similar.

^Tags: #monster #type_fiend