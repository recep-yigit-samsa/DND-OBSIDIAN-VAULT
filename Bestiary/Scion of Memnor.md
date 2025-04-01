# Scion of Memnor

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Scion of Memnor | Unknown | 26 | 656 (32d20 + 320) | 20 | walk: 60 ft., fly: {'number': 80, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Cloud Morningstar | 4d10 + 10 + 4d10 | - | - |
| Wind Javelin | 5d12 + 10 | 26 | - |
| Slam | 4d8 + 10 | - | - |
| Thunderous Vortex {@recharge 5} | 8d12 | 24 | - |


**Multiattack.** The scion makes one attack using Cloud Morningstar or Wind Javelin, as well as two Slam attacks.

**Cloud Morningstar.** {@atk mw} {@hit 18} to hit, reach 30 ft., one target. {@h}32 ({@damage 4d10 + 10}) force damage plus 22 ({@damage 4d10}) thunder damage.

**Wind Javelin.** {@atk rw} {@hit 18} to hit, range 120/480 ft., one target. {@h}42 ({@damage 5d12 + 10}) thunder damage, and the target must succeed on a {@dc 26} Strength saving throw or have the {@condition prone} condition.

**Slam.** {@atk mw} {@hit 18} to hit, reach 20 ft., one target. {@h}28 ({@damage 4d8 + 10}) force damage.

**Thunderous Vortex {@recharge 5}.** The scion magically creates a vortex of wind in a 60-foot-radius sphere centered on a point it can see within 120 feet of itself. Each creature in the sphere must succeed on a {@dc 24} Strength saving throw or be pulled straight toward the sphere's center, ending in an unoccupied space as close as possible to the center. Then a burst of thunder erupts in a 30-foot-radius sphere centered on the same point. Each creature in that area takes 52 ({@damage 8d12}) thunder damage and must succeed on a {@dc 24} Constitution saving throw or have the {@condition stunned} condition until the end of its next turn.

^Tags: #monster #type_unknown