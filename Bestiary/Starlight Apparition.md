# Starlight Apparition

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Starlight Apparition | Celestial | 5 | 72 (16d8) | 10 | walk: 0 ft., fly: {'number': 30, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Radiant Eruption | 5d6 + 3 | 14 | - |
| Possession {@recharge} | - | 14 | - |


**Radiant Eruption.** {@atk ms,rs} {@hit 6} to hit, reach 5 ft. or range 120 ft., one target. {@h}20 ({@damage 5d6 + 3}) radiant damage, and if the target is a creature, it must succeed on a {@dc 14} Wisdom saving throw or be {@condition blinded} for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Possession {@recharge}.** One Humanoid that the apparition can see within 5 feet of itself must succeed on a {@dc 14} Charisma saving throw or be possessed by the apparition; the apparition then disappears, and the target is {@condition incapacitated} and loses control of its body. The apparition now controls the body but doesn't deprive the target of awareness. The apparition can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being {@condition charmed} and {@condition frightened}. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. The possession lasts until the body drops to 0 hit points, the apparition ends it as a bonus action, the body leaves the Astral Plane, or the apparition is forced out by an effect like the {@spell dispel evil and good} spell. When the possession ends, the apparition reappears in an unoccupied space within 5 feet of the body. If it reappears in a location not on the Astral Plane, the apparition is destroyed. The target is immune to this apparition's Possession for 24 hours after succeeding on the saving throw or after the possession ends.

^Tags: #monster #type_celestial