# Miirym

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Miirym | Undead | 22 | 262 (25d10 + 125) | 10 | walk: 0 ft., fly: {'number': 60, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Bite | 9d6 + 3 | - | - |
| Breath Weapon {@recharge 5} | - | - | - |
| Cold Breath | 15d8 | 21 | - |
| Necrotic Breath | 15d10 | 21 | - |
| Paralyzing Breath | - | 21 | - |
| Frightful Presence | - | 21 | - |


**Bite.** {@atk mw} {@hit 10} to hit, reach 5 ft., one target. {@h}34 ({@damage 9d6 + 3}) force damage.

**Breath Weapon {@recharge 5}.** Miirym uses one of the following breath weapons:

**Cold Breath.** Miirym exhales an icy blast in a 90-foot cone. Each creature in that area must make a {@dc 21} Constitution saving throw, taking 67 ({@damage 15d8}) cold damage on a failed save, or half as much damage on a successful one.

**Necrotic Breath.** Miirym exhales a bolt of necrotic energy in a 120-foot line that is 10 feet wide. Each creature in that line must make a {@dc 21} Dexterity saving throw, taking 82 ({@damage 15d10}) necrotic damage on a failed save, or half as much damage on a successful one.

**Paralyzing Breath.** Miirym exhales paralyzing gas in a 90-foot cone. Each creature in that area must succeed on a {@dc 21} Constitution saving throw or be {@condition paralyzed} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Frightful Presence.** Each creature of Miirym's choice that is within 120 feet of her and aware of her must succeed on a {@dc 21} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Miirym's Frightful Presence for the next 24 hours.

^Tags: #monster #type_undead