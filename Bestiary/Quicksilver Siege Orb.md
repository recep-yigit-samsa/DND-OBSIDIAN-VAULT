# Quicksilver Siege Orb

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Quicksilver Siege Orb | Construct | 5 | 82 (15d6 + 30) | 15 | walk: 10 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Disk Blade (Disk Form Only) | 2d6 + 5 | - | - |
| Slam (Orb Form Only) | 2d4 + 5 | - | - |
| Slashing Run {@recharge 4} | 10d6 | 16 | - |


**Multiattack.** The quicksilver siege orb makes three Disk Blade or Slam attacks.

**Disk Blade (Disk Form Only).** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d6 + 5}) slashing damage.

**Slam (Orb Form Only).** {@atk mw} {@hit 8} to hit, reach 5 ft., one target. {@h}10 ({@damage 2d4 + 5}) bludgeoning damage.

**Slashing Run {@recharge 4}.** The quicksilver siege orb flies up to 20 feet in a straight line, then it flies up to 20 feet in a straight line in a different direction. During this move, it can move through the space of any Large or smaller creature. The first time it enters a creature's space during this move, that creature must make a {@dc 16} Dexterity saving throw, taking 35 ({@damage 10d6}) slashing damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_construct