# Veiled Presence

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Veiled Presence | Celestial | {'cr': '21', 'lair': '22'} | 300 (40d8 + 120) | 20 | walk: 40 ft., fly: {'number': 80, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Blade of Judgment | 1d6 + 7 + 6d8 | 22 | - |
| Revelation | - | 22 | - |


**Multiattack.** The veiled presence makes two Blade of Judgment attacks and can use Revelation.

**Blade of Judgment.** {@atk mw,rw} {@hit 14} to hit, reach 5 ft. or range 60 ft., one target. {@h}10 ({@damage 1d6 + 7}) piercing damage plus 27 ({@damage 6d8}) radiant damage. If the target is a creature, it must succeed on a {@dc 22} Charisma saving throw, or on its next turn, it can either move or take an action, but not both.

**Revelation.** The veiled presence reveals a glimpse of its otherworldly nature to a creature it can see within 30 feet of itself. The target must succeed on a {@dc 22} Wisdom saving throw or have the {@condition paralyzed} condition until the end of its next turn, after which the target is immune to this Revelation for 24 hours.

^Tags: #monster #type_celestial