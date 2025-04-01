# Solar Dragon Wyrmling

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Solar Dragon Wyrmling | Dragon | 3 | 51 (6d8 + 24) | 15 | walk: 20 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d6 + 3 + 1d6 | - | - |
| Tail | 1d4 + 3 | - | - |
| Photonic Breath {@recharge 5} | 4d10 | 14 | - |


**Multiattack.** The dragon makes one Bite attack and one Tail attack.

**Bite.** {@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage plus 3 ({@damage 1d6}) radiant damage.

**Tail.** {@atk mw} {@hit 5} to hit, reach 10 ft., one target. {@h}5 ({@damage 1d4 + 3}) bludgeoning damage.

**Photonic Breath {@recharge 5}.** The dragon exhales a flashing mote of radiant energy that travels to a point the dragon can see within 120 feet of itself, then blossoms into a 10-foot-radius sphere centered on that point. Each creature in the sphere must make a {@dc 14} Constitution saving throw, taking 22 ({@damage 4d10}) radiant damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_dragon