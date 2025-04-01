# Poltergeist

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Poltergeist | Undead | 2 | 22 (5d8) | 12 | walk: 5 ft., fly: {'number': 50, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Object Slam | 2d4 + 2 | - | - |
| Telekinetic Thrust | 2d6 + 2 | 12 | - |


**Multiattack.** The poltergeist makes one {@variantrule Object|XPHB} Slam attack and uses Telekinetic Thrust.

**Object Slam.** {@atkr m,r} {@hit 4}, reach 5 ft. or range 30 ft. {@h}7 ({@damage 2d4 + 2}) Bludgeoning damage.

**Telekinetic Thrust.** {@actSave str} {@dc 12}, one creature the poltergeist can see within 30 feet. {@actSaveFail} 9 ({@damage 2d6 + 2}) Force damage, and the target is pushed up to 30 feet straight away from the poltergeist.

^Tags: #monster #type_undead