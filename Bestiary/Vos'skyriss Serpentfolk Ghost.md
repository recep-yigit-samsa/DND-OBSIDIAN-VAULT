# Vos'skyriss Serpentfolk Ghost

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Vos'skyriss Serpentfolk Ghost | Undead | 4 | 55 (10d10) | 13 | walk: 0 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Spear | 1d6 + 3 + 2d6 | - | - |
| Etherealness | - | - | - |
| Terrifying Hiss | - | 13 | - |


**Multiattack.** The ghost makes two spear attacks.

**Spear.** {@atk mw,rw} {@hit 5} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage plus 7 ({@damage 2d6}) necrotic damage. If the ghost makes a ranged attack, its spear rematerializes in its hands after the attack is resolved.

**Etherealness.** The ghost enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.

**Terrifying Hiss.** The ghost emits an uncanny, rasping hiss. Each non-undead creature within 30 feet of the ghost that can hear it must succeed on a {@dc 13} Wisdom {@quickref saving throws|PHB|2|1|saving throw} or be {@condition frightened} for 1 minute. A {@condition frightened} target can repeat the {@quickref saving throws|PHB|2|1|saving throw} at the end of each of its turns, ending the condition on itself on a success. If a target's {@quickref saving throws|PHB|2|1|saving throw} is successful or the effect ends for it, the target is immune to this ghost's Terrifying Hiss for the next 24 hours.

^Tags: #monster #type_undead