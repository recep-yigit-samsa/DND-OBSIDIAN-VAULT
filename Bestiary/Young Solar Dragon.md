# Young Solar Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Young Solar Dragon | Dragon | 9 | 178 (17d10 + 85) | 16 | walk: 20 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 5 + 2d6 | - | - |
| Tail | 1d6 + 5 | - | - |
| Photonic Breath {@recharge 5} | 8d10 | 17 | - |


**Multiattack.** The dragon makes one Bite attack and one Tail attack.

**Bite.** {@atk mw} {@hit 9} to hit, reach 10 ft., one target. {@h}12 ({@damage 2d6 + 5}) piercing damage plus 7 ({@damage 2d6}) radiant damage.

**Tail.** {@atk mw} {@hit 9} to hit, reach 15 ft., one target. {@h}8 ({@damage 1d6 + 5}) bludgeoning damage.

**Photonic Breath {@recharge 5}.** The dragon exhales a flashing mote of radiant energy that travels to a point the dragon can see within 120 feet of itself, then blossoms into a 20-foot-radius sphere centered on that point. Each creature in the sphere must make a {@dc 17} Constitution saving throw, taking 44 ({@damage 8d10}) radiant damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon