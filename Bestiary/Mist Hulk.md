# Mist Hulk

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mist Hulk | Elemental | 6 | 94 (9d10 + 45) | 15 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 2d10 + 5 | - | - |
| Hideous Wailing {@recharge 5} | 4d6 | 14 | - |


**Multiattack.** The mist hulk makes two Slam attacks.

**Slam.** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d10 + 5}) cold damage.

**Hideous Wailing {@recharge 5}.** The mist hulk releases a wail infused with magical anguish. Each creature within 30 feet of it must make a {@dc 14} Wisdom saving throw. A creature in the mist hulk's space has disadvantage on the saving throw. On a failed save, a creature takes 14 ({@damage 4d6}) psychic damage and has the {@condition incapacitated} condition for 1 minute. The affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_elemental