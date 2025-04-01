# Ancient Solar Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Ancient Solar Dragon | Dragon | 21 | 425 (23d20 + 184) | 18 | walk: 30 ft., fly: {'number': 120, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 3d6 + 9 + 3d6 | - | - |
| Tail | 1d8 + 9 | - | - |
| Photonic Breath {@recharge 5} | 12d10 | 23 | - |


**Multiattack.** The dragon makes one Bite attack and one Tail attack.

**Bite.** {@atk mw} {@hit 16} to hit, reach 20 ft., one target. {@h}19 ({@damage 3d6 + 9}) piercing damage plus 10 ({@damage 3d6}) radiant damage.

**Tail.** {@atk mw} {@hit 16} to hit, reach 20 ft., one target. {@h}13 ({@damage 1d8 + 9}) bludgeoning damage.

**Photonic Breath {@recharge 5}.** The dragon exhales a flashing mote of radiant energy that travels to a point the dragon can see within 240 feet of itself, then blossoms into a 40-foot-radius sphere centered on that point. Each creature in the sphere must make a {@dc 23} Constitution saving throw, taking 66 ({@damage 12d10}) radiant damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon