# Adult Solar Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Adult Solar Dragon | Dragon | 14 | 200 (16d12 + 96) | 17 | walk: 30 ft., fly: {'number': 90, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d6 + 7 + 2d6 | - | - |
| Tail | 1d6 + 7 | - | - |
| Photonic Breath {@recharge 5} | 10d10 | 19 | - |


**Multiattack.** The dragon makes one Bite attack and one Tail attack.

**Bite.** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}14 ({@damage 2d6 + 7}) piercing damage plus 7 ({@damage 2d6}) radiant damage.

**Tail.** {@atk mw} {@hit 12} to hit, reach 20 ft., one target. {@h}10 ({@damage 1d6 + 7}) bludgeoning damage.

**Photonic Breath {@recharge 5}.** The dragon exhales a flashing mote of radiant energy that travels to a point the dragon can see within 180 feet of itself, then blossoms into a 30-foot-radius sphere centered on that point. Each creature in the sphere must make a {@dc 19} Constitution saving throw, taking 55 ({@damage 10d10}) radiant damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon